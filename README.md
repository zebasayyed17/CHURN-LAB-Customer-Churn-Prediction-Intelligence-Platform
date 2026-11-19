# ⚡ CHURN//LAB — Customer Churn Prediction & Intelligence Platform

### Predict Customer Churn. Understand Risk. Enable Smarter Retention.

CHURN//LAB is an interactive Machine Learning-powered customer churn prediction platform designed to identify customers who are likely to discontinue a service.

The project combines predictive analytics with a modern, interactive web interface to make customer churn insights more accessible and actionable.

Built with Python, Machine Learning, HTML, and Streamlit, CHURN//LAB transforms a traditional churn prediction model into an engaging application experience.

---

## 🚀 Project Overview

Customer churn is a major challenge for subscription-based businesses and service providers. Losing existing customers can affect revenue, customer lifetime value, and long-term business growth.

CHURN//LAB addresses this challenge through a predictive interface that uses customer information to estimate churn probability and help users understand customer retention risk.

**Project Focus:**
- Customer churn prediction
- Machine Learning-based risk estimation
- Interactive customer analytics experience
- Browser-side prediction logic
- Streamlit application integration

## ✨ Key Features

| Feature | Description |
|---|---|
| 🤖 Churn Prediction | Predict customer churn using a trained ML model |
| 📊 Risk Estimation | Display prediction results through an interactive interface |
| ⚡ Browser-Side Inference | Execute prediction logic directly within the HTML interface |
| 🎨 Premium UI | Custom cream and orange visual theme |
| 🖥️ Streamlit Integration | Host the HTML experience through Streamlit |
| 🔧 Modular Structure | Keep the UI, model asset, and application entrypoint organized |

## 🧠 How It Works

CHURN//LAB uses a browser-based prediction architecture.

**01 — Customer Input**

The user enters customer information through the interactive HTML interface.

**02 — Prediction Logic**

The HTML interface contains the model coefficients used for browser-side prediction.

**03 — Churn Estimation**

The browser executes the prediction logic and generates the result.

**04 — Interactive Experience**

Streamlit hosts the HTML interface and provides the application shell.

**Important:** The current HTML package performs inference using embedded model coefficients. The Streamlit host does not need to load the original pickle model during prediction.

## 🏗️ Application Architecture

```text
             USER
               |
               v
      Streamlit Application
               |
               v
     streamlit_app.py
               |
               v
 customer_churn_prediction.html
               |
               v
      Customer Input
               |
               v
   Browser-side Prediction Logic
               |
               v
      Churn Prediction Result
```

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Machine Learning | Trained Customer Churn Model |
| Frontend | HTML |
| Application Framework | Streamlit |
| Model Asset | Pickle |
| Prediction Execution | Browser-side JavaScript/HTML logic |

## 📁 Project Structure

```text
CHURN-LAB/
│
├── streamlit_app.py
│
├── customer_churn_prediction.html
│
├── churn_model.pkl
│
├── churnn.py
│
├── requirements.txt
│
└── .streamlit/
    └── config.toml
```

### File Description

| File | Purpose |
|---|---|
| `streamlit_app.py` | Streamlit application entrypoint |
| `customer_churn_prediction.html` | Complete visual interface and browser-side prediction logic |
| `churn_model.pkl` | Original trained model asset |
| `churnn.py` | Original Python/Streamlit implementation retained for reference |
| `requirements.txt` | Application dependencies |
| `.streamlit/config.toml` | Streamlit theme configuration |

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/CHURN-LAB.git
```

### 2. Navigate to the project directory

```bash
cd CHURN-LAB
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the environment

Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Streamlit application

```bash
streamlit run streamlit_app.py
```

The application will open in your browser.

## 🎯 Business Applications

CHURN//LAB demonstrates how predictive analytics can support customer retention strategies across:

- Telecommunications
- Subscription-based services
- Banking and financial services
- E-commerce
- SaaS businesses

Potential business applications include identifying customers who may need retention attention, supporting targeted engagement, and helping teams prioritize customer relationships.

## 🔮 Future Enhancements

- Customer-level churn risk segmentation
- Explainable AI using SHAP
- Retention strategy recommendations
- Customer lifetime value analysis
- Model performance and evaluation dashboard
- Integration with customer analytics datasets
- Deployment with a production-ready inference API

## 👩‍💻 Author

### Zeba Sayyed

**Data Science & Analytics | Machine Learning | Generative AI**

[![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/zebasayyed17)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/zeba-sayyed-28766941b/)

---

⭐ If you find this project interesting, consider giving the repository a star!

*Turning customer data into predictive intelligence.*
