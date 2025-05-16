## 🍼 ML for Pregnancy Prediction

This project aims to develop a machine learning model that predicts the likelihood of pregnancy based on health survey data. It leverages feature engineering and model training techniques to improve prediction accuracy. Key tools used include CatBoost, Pandas, Jupyter Notebook, and Conda for environment management.

---

## 📁 Project Structure

```
ML-for-pregnancy-prediction/
├── README.md                  # Project introduction and instructions
├── .gitignore                 # Git ignore rules
├── code/
│   └── ONBOARD.ipynb          # Main Jupyter Notebook containing code
├── Dataset/
│   ├── train.csv              # Training dataset
│   ├── test.csv               # Test dataset
│   └── *.xlsx                 # Original Excel data (filename has encoding issues)
├── env/
│   ├── env.yml                # Conda environment configuration (general)
│   ├── env_mac.yml            # Conda environment configuration (for macOS)
│   └── catboost_info/         # CatBoost training logs and metrics
```

---

## ▶️ How to Run

1. **Set Up the Environment**

   Create the required Conda environment using the provided environment file:

   ```bash
   conda env create -f env/env.yml
   conda activate pregnancy-prediction
   ```

   For macOS users:

   ```bash
   conda env create -f env/env_mac.yml
   ```

2. **Launch the Jupyter Notebook**

   Run the following command to start Jupyter and open the notebook:

   ```bash
   jupyter notebook
   ```

   Then open `code/ONBOARD.ipynb` to explore and execute the code.

3. **Dataset**

   The `Dataset` folder includes the processed `train.csv` and `test.csv` files. If needed, the original `.xlsx` file can be used to regenerate or verify the datasets.
