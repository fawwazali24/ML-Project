# Machine Learning Pipeline

This project demonstrates the development of a **production-grade, end-to-end machine learning pipeline** using modular programming practices. The pipeline covers the complete ML lifecycle — from **data ingestion**, **data transformation**, **model training**, and **prediction**, to **deployment** — all structured for scalability and maintainability.

---

## 🛠️ Tech Stack

- **Python**
- **scikit-learn**
- **pandas**, **NumPy**
- **Modular OOP design**
- **Logging & Exception Handling**

---

## ⚙️ Key Modules

- **`components/`**
  - `data_ingestion.py`: Scripts for ingesting raw data from source.
  - `data_transformation.py`: Handles data cleaning and feature engineering.
  - `model_trainer.py`: Contains model training logic.

- **`pipeline/`**
  - `predict_pipeline.py`: Manages predictions using the trained model.

- **`exception.py`**: Custom exception classes for robust error handling.
- **`logger.py`**: Centralized logging for better traceability.
- **`utils.py`**: Utility functions used across modules.

- **`app.py`**: The web application server for serving predictions.

---




