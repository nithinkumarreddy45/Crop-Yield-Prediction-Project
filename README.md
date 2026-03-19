   # 🌱 AgriPredict India: Smart Crop Yield Dashboard

<p align="center">
  <img src="https://sageuniversity.edu.in/assets/images/blog/role-of-artificial-intelligence-in-agriculture.jpg" alt="AgriPredict Main Dashboard Preview" width="1000">
</p>

---
> An advanced, data-driven agricultural dashboard designed to empower Indian farmers with Machine Learning-based crop yield predictions, live market prices, and expert pest advisories.

## 📖 About The Project

**AgriPredict India** bridges the gap between modern data science and traditional farming. By leveraging a **K-Nearest Neighbors (KNN)** machine learning model trained on historical agricultural data, this tool allows farmers to input their specific field parameters (soil nutrients, rainfall, area) and receive an instant, accurate estimate of their crop yield. 

Beyond just prediction, the platform serves as a complete command center for farmers, offering real-time market data and actionable agronomic advice.

## ✨ Key Features

* 🎯 **ML-Powered Yield Prediction:** Uses KNN to estimate yield based on N-P-K levels, rainfall, season, and location.
* 📊 **Smart Crop Assessment:** Automatically analyzes predicted yields and suggests alternative crops (Crop Rotation) if conditions are suboptimal.
* 📈 **Live Mandi Prices:** Spot prices for major cereals, cash crops, and vegetables across various Indian states.
* 🐛 **Pest & Disease Advisory:** Actionable, color-coded alerts (High Alert, Watch, Advisory) based on current weather patterns and ICAR guidelines.
* 🖨️ **Exportable PDF Reports:** A foolproof, native print engine that generates beautiful, distraction-free PDF reports of yield predictions.

---

## 📸 Interface Gallery

Here is a closer look at the platform's core modules:

### 1. The Yield Predictor
![Yield Predictor Tool]([ADD_PREDICTOR_TAB_IMAGE_LINK_HERE])
*Interactive form calculating real-time yield estimates and smart recommendations.*

### 2. Market Prices Dashboard
![Live Market Prices]([ADD_MARKET_TAB_IMAGE_LINK_HERE])
*Tracking spot prices for crops like Wheat, Cotton, and Soybean across India.*

### 3. Pest Advisory System
![Pest Advisory Alerts]([ADD_ADVISORY_TAB_IMAGE_LINK_HERE])
*Early warning system for threats like Fall Armyworm and Yellow Rust.*

### 4. Printable PDF Report
![PDF Export View]([ADD_PRINT_REPORT_IMAGE_LINK_HERE])
*Clean, structured output for record-keeping and offline reference.*

---

## 🛠️ Tech Stack

### Frontend (UI/UX)
* **HTML5**
* **Tailwind CSS** (for responsive, modern glass-morphism design)
* **Vanilla JavaScript** (DOM manipulation, native print handling)
* **FontAwesome** (Iconography)

### Backend & Machine Learning
* **Python**
* **Scikit-Learn** (K-Nearest Neighbors Regressor)
* **Pandas & NumPy** (Data processing and cleaning)
* **Jupyter Notebook** (Model training and evaluation)

---

## 🗄️ The Dataset

The underlying ML model is trained on a comprehensive dataset (`dataset.csv`) tracking historical agricultural metrics. Key features fed into the model include:
* `State / Union Territory`
* `Crop Type` & `Season`
* `Area Planted & Harvested` (Acres/Hectares)
* `Nitrogen (N), Phosphorous (P), Potash (K)` (Pounds per Acre / Kg per Ha)
* **Target Variable:** `Lint/Crop Yield` 

---

## 🚀 Getting Started

### Prerequisites
To interact with the frontend, all you need is a modern web browser (Chrome, Edge, Firefox, Safari).

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/AgriPredict-India.git](https://github.com/your-username/AgriPredict-India.git)
