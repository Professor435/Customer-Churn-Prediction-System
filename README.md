# Customer-Churn-Prediction-System

---
## 📁 Download the Application

**[ChurnShield AI - Customer Churn Prediction System](sandbox:///mnt/agents/output/churnshield_ai.html)**

Simply download and open the HTML file in any modern browser. No server or installation required!

---

## ✨ Features Included

| Feature | Description |
|---------|-------------|
| **🎯 Single Customer Prediction** | 17 input fields (tenure, contract, services, billing, etc.) with real-time churn probability calculation |
| **📤 Batch Upload** | CSV/XLSX drag-and-drop upload with simulated batch prediction results |
| **📊 Interactive Dashboard** | 4 live Chart.js visualizations (Churn Trend, Distribution, Contract Analysis, Service Analysis) |
| **👥 Customer Records Table** | Sortable, searchable, filterable table with risk score progress bars and status badges |
| **🧠 Model Performance** | Confusion Matrix, ROC Curve, Accuracy/Precision/Recall/F1/AUC metrics |
| **📈 Feature Importance** | Animated progress bars showing which features drive churn |
| **🎨 Customer Segmentation** | High/Medium/Low risk cards with automatic population |
| **🔔 Toast Notifications** | Success/info/error feedback for all actions |
| **📄 Export Reports** | One-click report export functionality |
| **🎭 Modern Dark UI** | Glassmorphism design, animated gradients, floating shapes, smooth transitions |
| **📱 Responsive Design** | Works seamlessly on desktop, tablet, and mobile |

---

## 🐙 GitHub Repository Description

Here's a professional `README.md` description for your repo:

```markdown
# 🛡️ ChurnShield AI — Customer Churn Prediction System

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)]()
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)]()
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs&logoColor=white)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg)]()

> **AI-powered customer churn prediction with real-time analytics, risk segmentation, and actionable retention insights.**

ChurnShield AI is a fully client-side Customer Churn Prediction System built with pure HTML, CSS, and JavaScript. It simulates machine learning model behavior to predict customer churn probability, visualize trends, and help businesses proactively retain their customers.

---

## 🚀 Live Demo

Open `index.html` in your browser — no server, no dependencies, no installation!

---

## ✨ Key Features

### 🔮 Prediction Engine
- **Single Customer Prediction** — Input 17 customer attributes and get instant churn probability with risk factors
- **Batch Processing** — Upload CSV/XLSX files for bulk churn prediction
- **Smart Risk Scoring** — Weighted algorithm based on contract type, tenure, charges, services, and demographics

### 📊 Analytics Dashboard
- **Churn Trend Analysis** — Time-series line chart showing churn vs retention over time
- **Distribution Charts** — Doughnut and bar charts for churn breakdown by contract and service type
- **Customer Segmentation** — Automatic categorization into High/Medium/Low risk segments

### 🧠 Model Insights
- **Confusion Matrix** — Visual TP/FP/FN/TN breakdown
- **ROC Curve** — Model performance visualization with AUC score
- **Feature Importance** — Ranked feature contributions to churn prediction
- **Performance Metrics** — Accuracy, Precision, Recall, F1-Score, AUC-ROC

### 🎨 Modern UI/UX
- **Glassmorphism Design** — Frosted glass cards with backdrop blur
- **Animated Gradients** — Floating shapes and dynamic backgrounds
- **Dark Theme** — Professional dark mode with vibrant accent colors
- **Fully Responsive** — Optimized for desktop, tablet, and mobile devices
- **Toast Notifications** — Real-time feedback for all user actions

### 📋 Data Management
- **150 Sample Records** — Generate realistic customer datasets instantly
- **Search & Filter** — Find customers by ID, contract, or status
- **Pagination** — Smooth navigation through large datasets
- **Export Reports** — Download prediction results and analytics

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic structure & accessibility |
| **CSS3** | Glassmorphism, animations, gradients, responsive grid |
| **Vanilla JavaScript** | Prediction logic, data management, DOM manipulation |
| **Chart.js** | Interactive data visualizations |
| **Font Awesome** | Professional iconography |
| **Google Fonts (Inter)** | Modern typography |

---

## 📂 Project Structure

```
churnshield-ai/
├── index.html          # Main application (single file)
├── README.md           # Documentation
└── assets/
    ├── css/            # Stylesheets (embedded in HTML)
    ├── js/             # Application logic (embedded in HTML)
    └── demo-data/      # Sample datasets
```

---

## 🎯 How It Works

1. **Input Customer Data** — Fill in customer attributes like tenure, contract type, monthly charges, and services
2. **Get Prediction** — The simulated ML model calculates churn probability based on weighted feature importance
3. **View Risk Factors** — See exactly which factors contribute to the churn risk
4. **Analyze Trends** — Explore dashboards to understand churn patterns across your customer base
5. **Take Action** — Use segmentation data to target high-risk customers with retention strategies

---

## 🧮 Prediction Algorithm

The system uses a **weighted probability model** that simulates real machine learning behavior:

```javascript
Base Probability: 15%
+ Contract Type (up to +25% for month-to-month)
+ Tenure (up to +20% for < 12 months)
+ Monthly Charges (up to +15% for high values)
+ Internet Service (+12% for fiber optic)
+ Payment Method (+8% for electronic check)
+ Add-ons (-8% for security/support features)
= Final Churn Probability (0-100%)
```

---

## 🚀 Getting Started

### Option 1: Direct Open
```bash
# Simply open the HTML file in your browser
open index.html
```

### Option 2: Local Server (for development)
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```

Then navigate to `http://localhost:8000`

---

## 📊 Sample Data

Click **"Load Sample Data"** to generate 150 realistic customer records with:
- Varied contract types and tenures
- Realistic pricing and service combinations
- Simulated churn outcomes based on feature correlations

---

## 🎨 Customization

### Changing Color Theme
Edit CSS variables in the `:root` selector:
```css
:root {
    --primary: #6366f1;      /* Main accent */
    --secondary: #ec4899;    /* Secondary accent */
    --success: #10b981;      /* Success states */
    --warning: #f59e0b;      /* Warning states */
    --danger: #ef4444;       /* Danger states */
}
```

### Adding New Features
Extend the prediction form and update the `predictChurn()` function with new feature weights.

---

## 🔮 Future Enhancements

- [ ] Integration with real ML backend (Python/Flask or Node.js/Express)
- [ ] User authentication and role-based access
- [ ] Email alert system for high-risk customers
- [ ] Advanced filtering and cohort analysis
- [ ] Export to PDF/Excel with detailed reports
- [ ] Real-time data streaming via WebSockets

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 🙏 Acknowledgments

- [Chart.js](https://www.chartjs.org/) for beautiful visualizations
- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for Inter typography

---

<p align="center">
  <b>Built with ❤️ to help businesses retain their customers</b><br>
  <i>Star ⭐ this repo if you find it helpful!</i>
</p>
```

---

## 🖼️ Preview Highlights

The application includes:
- **Animated gradient backgrounds** with floating shapes
- **Glassmorphism cards** with backdrop blur effects
- **Interactive charts** powered by Chart.js
- **Real-time form validation** and prediction
- **Professional color coding** (red for churn, green for retention, amber for risk)
- **Smooth animations** on hover, scroll, and state changes

Open the file and explore all tabs: **Dashboard → Predict → Analytics → Customers → Model**!

for more contact (professorshami435@gmail.com)
