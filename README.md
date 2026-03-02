## 1. Project Overview
This project develops a predictive pipeline to identify high-intent website sessions (characterised by a **15.5% class imbalance**) using a **Tuned Random Forest** model.

### Key Performance Summary:
* **Champion Model:** Tuned Random Forest.
* **Primary Metric:** PR-AUC (Average Precision) = **0.723**.
* **Decision Threshold:** 0.400 (Achieving a balanced **0.666 F1-score**).

---

## 2. Data Access Instructions
The dataset used is the **Online Shoppers Purchasing Intention Dataset** from the UCI Machine Learning Repository.

* **Download:** Access the official dataset [here](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset).
* **Placement:** Download and unzip the file, then move `online_shoppers_intention.csv` into the `data/raw/` directory to ensure the automated pipeline functions correctly.
* **Licensing:** Data is provided under **CC BY 4.0** for academic and commercial use.
* **Data Note:** The dataset contains 12,330 sessions with 18 features, primarily focusing on session-level behavioural metrics.

---

## 3. Environment Specification
This project requires **Python 3.9+**. All specific version dependencies are managed within the `requirements.txt` file.

### **Installation:**
```bash
pip install -r requirements.txt