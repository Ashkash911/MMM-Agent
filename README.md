# MMM Assistant - Marketing Mix Model Builder

A modern React application for building Google Meridian Marketing Mix Models (MMM) with an intuitive step-by-step workflow and AI-powered chat assistant.

## ✨ Features

- **5-Step Workflow**: Setup → Data Upload → Model Config → Training → Results
- **Interactive Chat Interface**: AI assistant guides you through each step
- **Visual Progress Tracking**: Clear status indicators for each step and substep
- **Responsive Design**: Modern UI with Tailwind CSS
- **Real-time Updates**: Dynamic status updates as you progress
- **Data Widgets**: Context-aware content for each workflow step

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. **Clone and install dependencies:**
   ```bash
   npm install
   ```

2. **Start the development server:**
   ```bash
   npm run dev
   ```

3. **Open your browser:**
   Navigate to `http://localhost:5173`

## 🏗️ Project Structure

```
src/
├── components/
│   ├── ui/                 # Reusable UI components
│   │   ├── button.tsx
│   │   ├── card.tsx
│   │   ├── input.tsx
│   │   └── scroll-area.tsx
│   ├── StepProgress.tsx    # Workflow step navigation
│   ├── ChatInterface.tsx   # AI chat interface
│   └── DataWidget.tsx      # Step-specific content widgets
├── hooks/
│   └── use-toast.ts        # Toast notification hook
├── lib/
│   └── utils.ts            # Utility functions
├── App.tsx                 # Main application component
├── main.tsx                # Application entry point
└── index.css               # Global styles and Tailwind
```

## 🎯 How It Works

### 1. Project Setup
- Configure project basics
- Select target KPI
- Set analysis period

### 2. Data Upload
- Upload CSV/XLSX files
- Automatic data validation
- Channel mapping

### 3. Model Configuration
- Auto-generated defaults
- Parameter review
- Prior settings

### 4. Model Training
- Meridian MMM execution
- Convergence monitoring
- Diagnostic checks

### 5. Results & Optimization
- ROI analysis by channel
- Budget optimization
- Scenario planning

## 🎨 UI Components

- **StepProgress**: Left sidebar with workflow navigation
- **DataWidget**: Center area with step-specific content
- **ChatInterface**: Right-side AI chat with scrollbar and message differentiation

## 🔧 Customization

### Adding New Steps
1. Update `initialSteps` in `App.tsx`
2. Add corresponding logic in `handleBotResponse`
3. Create widget content in `DataWidget.tsx`

### Styling
- Uses Tailwind CSS with custom CSS variables
- Responsive design with mobile-first approach
- Custom color scheme for different message types

## 📱 Responsive Design

- **Desktop**: Full three-column layout
- **Tablet**: Adaptive layout with collapsible sidebar
- **Mobile**: Stacked layout for small screens

## 🚀 Deployment

### Build for Production
```bash
npm run build
```

### Preview Production Build
```bash
npm run preview
```

## 🛠️ Tech Stack

- **Frontend**: React 18 + TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Build Tool**: Vite
- **State Management**: React Hooks

## 📄 License

MIT License - feel free to use this project for your own MMM applications!

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📞 Support

For questions or issues, please open a GitHub issue or contact the development team.

---

**Built with ❤️ for Marketing Mix Modeling professionals** 