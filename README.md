# Accelno
<!-- 🚗 -->

A modern React application built with Vite, featuring a comprehensive dashboard with data visualization capabilities.

## 🚀 Features

- **Modern React Stack**: Built with React 18 and Vite for fast development and optimal performance
- **State Management**: Redux Toolkit for efficient state management
- **Routing**: React Router DOM for seamless navigation
- **UI Components**: Flowbite React components with Tailwind CSS styling
<!-- - **🎨 UI Components**: Beautiful Flowbite React components with Tailwind CSS styling -->
- **Data Visualization**: Multiple charting libraries including ApexCharts, Recharts, and Nivo
<!-- - **📊 Data Visualization**: Rich charting capabilities with ApexCharts, Recharts, Nivo, and Lightweight Charts -->
- **Interactive Elements**: Drag & drop functionality, resizable components, and responsive layouts
<!-- - **🎯 Interactive Elements**: Advanced drag & drop functionality, resizable components, and fully responsive layouts -->
- **Form Handling**: React Hook Form with Yup validation
<!-- - **📝 Form Handling**: Robust form management with React Hook Form and Yup validation -->
- **Payment Integration**: Stripe integration for payment processing


## 🛠️ Tech Stack

- **Frontend**: React 18, Vite
- **Styling**: Tailwind CSS, Flowbite
- **State Management**: Redux Toolkit, Redux Persist
- **Routing**: React Router DOM
- **Charts**: ApexCharts, Recharts, Nivo, Lightweight Charts


3. Set up environment variables:
```bash
cp .env.sample .env
# Edit .env with your configuration
```

## 🏃‍♂️ Development

Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 📁 Project Structure

```
src/
├── api/          # API integration
├── assets/       # Static assets
├── client/       # Client configuration
├── components/   # Reusable components
├── hooks/        # Custom React hooks
├── layouts/      # Layout components
├── pages/        # Page components
├── redux/        # Redux store and slices
├── screens/      # Screen components
├── services/     # Service layer
├── utils/        # Utility functions
├── App.jsx       # Main App component
├── main.jsx      # Application entry point
└── routes.jsx    # Route definitions
```

## 🚀 Deployment

The project is configured for Netlify deployment with the included `netlify.toml` configuration file.

To deploy:
1. Build the project: `npm run build`
2. Deploy the `dist` folder to your hosting platform

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/new-feature`
3. Commit your changes: `git commit -am 'Add new feature'`
4. Push to the branch: `git push origin feature/new-feature`
5. Submit a pull request

## 📄 License

This project is private and proprietary.
