# PharmacoDose Predictor

🎯 **Desktop application to assist with accurate therapeutic dose prediction based on Random Forest machine learning.**

## 🧪 Context

This platform is designed for **clinical pharmacologists**, particularly those working on diseases such as **tuberculosis**, where precise dosage is critical to achieving a **therapeutic drug concentration**.

The application workflow:

1. Select the **post-transplantation duration** (≥ 80 or < 80 days).
2. Enter the **patient's clinical information**.
3. Get an **automatically predicted optimal dose** using a trained **Random Forest model**.

## 🖥️ Technologies Used

- ⚡ **Electron.js** – for the cross-platform desktop interface  
- 🐍 **Python** – for dose prediction through `predict_model.py`  
- 🌲 **Random Forest (scikit-learn)** – supervised machine learning model  
- 🔗 `python-shell` – to connect Node.js with Python scripts  

## 📷 Screenshots

*You can include screenshots here such as `screenshot1.png`, `screenshot2.png`*

## 🛠️ Installation

1. **Clone the repository**:

```bash
git clone https://github.com/<your-username>/pharmaco-dose-predictor.git
cd pharmaco-dose-predictor
