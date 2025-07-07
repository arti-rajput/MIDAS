# SoilSpectraML: Real-time Soil Property Prediction from Spectral Input

A lightweight, interactive web app built using Python and Streamlit to predict soil properties from spectral data inputs using trained machine learning models. Achieves ~70% accuracy on real-world spectral datasets.

---

## 📌 Overview

**SoilSpectraML** is a research-driven web application designed to provide real-time predictions of soil properties based on input spectral signatures. Developed for agronomic researchers and soil scientists, it bridges machine learning and spectral data processing through a user-friendly browser-based tool.

This tool was developed while working at ICAR-INDIAN INSTITUTE OF SOIL SCIENCE as part of a soil analysis and digital agriculture initiative.

---

## 🚀 Features

- 🧪 **Predict Soil Properties**  
  Input spectral vectors and receive predicted values like organic carbon, nitrogen content, etc.

- ⚙️ **ML Model Integration**  
  Trained on curated soil spectral datasets with ~70% prediction accuracy.

- 🖥️ **Streamlit UI**  
  Intuitive interface for researchers to upload data, visualize results, and iterate.

- 📈 **Result Visualization**  
  View predictions alongside basic statistical summaries.

---

## 🧰 Tech Stack

- **Language:** Python
- **Framework:** Streamlit
- **ML Libraries:** scikit-learn, pandas, numpy
- **Data Handling:** CSV, NumPy arrays
- **Model Deployment:** Local or Streamlit Cloud

---

## ⚙️ Installation & Running

### 🔧 Prerequisites
- Python 3.8+
- `pip install -r requirements.txt`

### ▶️ Run Locally

```bash
# Clone the repository
git clone https://github.com/arti-rajput/MIDAS.git
cd MIDAS

# Install dependencies
pip install -r requirements.txt

# Launch the app
streamlit run app.py
