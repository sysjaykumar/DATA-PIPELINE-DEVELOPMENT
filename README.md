# 📊 ETL Pipeline using Pandas & Scikit-learn

This project demonstrates an **Extract → Transform → Load (ETL)** pipeline for preprocessing, transforming, and saving datasets using **Pandas** and **Scikit-learn**.  
It works with the provided `data.csv` file but can be adapted to other datasets.

---

## 🚀 Features
- **Extract**  
  - Load dataset from CSV.
  - Explore shape, missing values, and data types.

- **Transform**  
  - Handle missing values (mean for numeric, most frequent for categorical).
  - Encode categorical variables using OneHotEncoder.
  - Scale numeric features with StandardScaler.
  - Remove duplicates.

- **Load**  
  - Save processed datasets to `processed_train.csv` and `processed_test.csv`.

---

## 📂 Project Structure
```
├── data.csv                # Raw input dataset (uploaded by user)
├── etl_pipeline.ipynb      # Jupyter Notebook with ETL process
├── processed_train.csv     # Cleaned and transformed training data
├── processed_test.csv      # Cleaned and transformed testing data
└── README.md               # Project documentation
```

---

## ⚙️ Requirements
Make sure you have the following Python libraries installed:

```bash
pip install pandas numpy scikit-learn seaborn
```

---

## 🖥 How to Run
1. **Clone the repository**
```bash
git clone https://github.com/yourusername/etl-pipeline.git
cd etl-pipeline
```

2. **Place your dataset**
   - Put your `data.csv` in the project root folder.  
   - Or modify the notebook to load your own dataset path.

3. **Run Jupyter Notebook**
```bash
jupyter notebook etl_pipeline.ipynb
```

4. **Follow the ETL steps**
   - Extract → Transform → Load  
   - The processed CSV files will be saved automatically.

---

## 📝 Customization
- Change the `TARGET_COLUMN` in the notebook to match your dataset's target variable.
- Adjust preprocessing steps in the `numeric_pipeline` and `categorical_pipeline` if needed.

---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Author
**Your Name**  
Data Science & Machine Learning Enthusiast
