# NeuroStock AI - Demand Forecasting & Inventory Optimization System

## Project Overview

NeuroStock AI is an advanced machine learning-powered platform designed to revolutionize demand forecasting and inventory management for businesses of all sizes. The system combines cutting-edge AI algorithms with an intuitive web interface to help organizations predict sales trends, optimize stock levels, and reduce operational costs.

## Technologies Used

### Frontend Technologies
- **Next.js 16.0.3** - React framework for server-side rendering and static site generation
- **React 19.2.0** - Modern React library for building user interfaces
- **TypeScript** - Type-safe JavaScript for better code quality and maintainability
- **Tailwind CSS 4.1.9** - Utility-first CSS framework for rapid UI development
- **Radix UI** - Comprehensive set of accessible UI components
- **Recharts** - Data visualization library for creating interactive charts
- **Lucide React** - Beautiful and consistent icon library

### Backend & Machine Learning
- **Python 3.x** - Core programming language for ML services
- **FastAPI 0.104.1** - Modern, fast web framework for building APIs
- **Uvicorn 0.24.0** - ASGI server for running FastAPI applications
- **Scikit-learn 1.3.2** - Machine learning library for predictive modeling
- **Pandas 2.1.3** - Data manipulation and analysis library
- **NumPy 1.26.0** - Numerical computing library
- **Plotly 5.17.0** - Interactive graphing and visualization library

### Machine Learning Models
- **Prophet** - Facebook's time series forecasting model
- **LSTM (Long Short-Term Memory)** - Deep learning model for sequence prediction
- **ARIMA** - AutoRegressive Integrated Moving Average model
- **XGBoost** - Gradient boosting framework for structured data
- **Linear Regression** - Classical statistical modeling approach
- **K-Means Clustering** - Unsupervised learning for product segmentation

### Database & Infrastructure
- **MongoDB** - NoSQL database for flexible data storage
- **Mongoose** - MongoDB object modeling for Node.js

## Real-World Applications

### Retail & E-commerce
- **Sales Prediction**: Forecast product demand across different categories and locations
- **Seasonal Planning**: Anticipate demand spikes during holidays and special events
- **Product Clustering**: Group similar products for efficient inventory management

### Supply Chain Management
- **Stock Optimization**: Maintain optimal inventory levels to prevent stockouts and overstocking
- **Reorder Point Calculation**: Automated alerts when inventory reaches critical levels
- **Safety Stock Determination**: Calculate buffer stock to handle demand variability

### Business Intelligence
- **Demand Pattern Analysis**: Identify trends, seasonality, and cyclical patterns
- **Performance Metrics**: Track forecast accuracy and model effectiveness
- **Real-time Dashboard**: Interactive visualizations for decision-making

### Cost Reduction
- **Reduced Holding Costs**: Minimize excess inventory and storage expenses
- **Prevented Lost Sales**: Avoid revenue loss from stockouts
- **Improved Cash Flow**: Optimize working capital through better inventory turnover

## Key Features

### 🧠 Advanced Forecasting
- Multiple ML models (Prophet, LSTM, ARIMA, XGBoost, Regression)
- Ensemble model combining predictions for improved accuracy
- Customizable forecast horizons (1-365 days)

### 📊 Interactive Dashboard
- Real-time inventory monitoring
- Visual demand trend analysis
- Performance metrics and KPIs

### 🔔 Smart Alerts
- Low stock notifications
- Reorder point reminders
- Anomaly detection in demand patterns

### 📈 Product Clustering
- K-Means clustering for demand pattern grouping
- Seasonality-based product categorization
- ABC analysis for inventory prioritization

### 🌐 Modern Web Interface
- Responsive design for all devices
- Dark/light theme support
- Accessible UI components

## Project Architecture

```
NeuroStock AI/
├── Frontend (Next.js + TypeScript)
│   ├── User Interface Components
│   ├── Dashboard & Analytics
│   └── Data Visualization
├── Backend (FastAPI + Python)
│   ├── ML Model Services
│   ├── API Endpoints
│   └── Data Processing
└── Database (MongoDB)
    ├── Historical Sales Data
    ├── Inventory Records
    └── Model Predictions
```

## Getting Started

### Prerequisites
- Node.js 18+ and npm/pnpm
- Python 3.8+
- MongoDB instance

### Installation
1. Clone the repository
2. Install frontend dependencies: `npm install` or `pnpm install`
3. Set up Python environment: `python -m venv venv && source venv/bin/activate`
4. Install ML dependencies: `pip install -r requirements.txt`
5. Start frontend: `npm run dev`
6. Start ML service: `python ml_service/main.py`

## Usage

1. **Data Upload**: Upload historical sales data in CSV format
2. **Model Training**: Select ML models for forecasting
3. **Generate Forecasts**: Choose prediction horizon and run predictions
4. **View Results**: Analyze forecasts through interactive dashboards
5. **Optimize Inventory**: Use insights to manage stock levels

## Project Contributors

**Lead Developer: Pavani**
- Designed and implemented the complete demand forecasting system
- Developed machine learning models including Prophet, LSTM, ARIMA, and XGBoost
- Built the full-stack web application using Next.js and FastAPI
- Created interactive dashboards and data visualization components
- Implemented product clustering and inventory optimization algorithms
- Integrated multiple ML models into an ensemble forecasting system

Pavani's expertise in machine learning, full-stack development, and data science was instrumental in creating this comprehensive demand forecasting solution that combines advanced AI algorithms with practical business applications.


## Contact

For questions or support regarding this project, please reach out to the development team.
