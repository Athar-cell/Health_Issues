# ☕ Health Issues Analysis

This project analyzes the relationship between **coffee consumption** and **various health metrics** using a synthetic dataset.  
It includes data cleaning, visualization, encoding, and model training using a Random Forest classifier.

---

## 📋 Features
- Handles missing data
- Encodes categorical variables
- Visualizes health-related parameters
- Scales features for model training
- Trains a Random Forest model to predict health issues

---

## 📁 Project Structure
```
├── Health_Issues.ipynb        # Original Jupyter notebook
├── Health_Issues_Clean.py     # Cleaned Python version of the notebook
├── cleaned_coffee_health_data.csv  # Processed dataset (generated after running script)
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
```

---

## ⚙️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Health_Issues_Analysis.git
   cd Health_Issues_Analysis
   ```

2. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate    # For Linux/Mac
   venv\Scripts\activate     # For Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the script:
   ```bash
   python Health_Issues_Clean.py
   ```

---

## 📊 Output
- Visualizations of coffee intake, BMI, sleep quality, and other parameters.
- A trained Random Forest model that predicts health issues.
- A cleaned CSV file `cleaned_coffee_health_data.csv`.

---

## 🧠 Technologies Used
- Python 3.x
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## ✨ Author
**Athar Sharma**  
📧 [atharsharma86@gmail.com](mailto:atharsharma86@gmail.com)

---

## 📜 License
This project is open-source and available under the MIT License.
