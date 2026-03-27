# 🫀 EDA and Feature Engineering Project on Heart Failure Dataset

> Analyzing clinical records to uncover patterns in heart failure — turning raw medical data into actionable insights.

---

## 📌 Table of Contents

- [📖 Project Overview](#-project-overview)
- [📂 Project Repository Structure](#-project-repository-structure)
- [📊 Dataset Information](#-dataset-information)
- [⚙️ Technologies Used](#️-technologies-used)
- [📈 EDA Highlights](#-eda-highlights)
- [🛠️ Feature Engineering Steps](#️-feature-engineering-steps)
- [🖼️ Visualizations](#️-visualizations)
- [🚀 How to Run](#-how-to-run)
- [🤝 Contributing](#-contributing)

---

## 📖 Project Overview

This project performs in-depth **Exploratory Data Analysis (EDA)** and **Feature Engineering** on the **Heart Failure Clinical Records Dataset**. Heart failure is a critical medical condition, and understanding the factors that contribute to it can be life-saving.

Through this project, we explore clinical features such as blood pressure, ejection fraction, serum creatinine, and more — uncovering hidden patterns, correlations, and risk indicators that can help build better predictive models for heart failure survival.

---

## 📂 Project Repository Structure

```
EDA_and_Feature_Engineering_Project_on_Heart_Failure_Dataset/
│
├── EDA and Feature Engineering Project on Heart Failure Dataset/
│   ├── EDA and Feature Engineering on Heart Failure Dataset.ipynb
│   ├── heart_failure_clinical_records_dataset.csv
│   └── README.md
│
└── Histogram of High Blood Pressure.png
```

---

## 📊 Dataset Information

- **Dataset Name:** `heart_failure_clinical_records_dataset.csv`
- **Domain:** Healthcare / Medical
- **Key Clinical Features Include:**

| Feature | Description |
|---------|-------------|
| `age` | Age of the patient (years) |
| `anaemia` | Decrease of red blood cells (boolean) |
| `creatinine_phosphokinase` | Level of CPK enzyme in the blood |
| `diabetes` | Whether the patient has diabetes (boolean) |
| `ejection_fraction` | Percentage of blood leaving the heart per contraction |
| `high_blood_pressure` | Whether the patient has hypertension (boolean) |
| `platelets` | Platelets in the blood (kiloplatelets/mL) |
| `serum_creatinine` | Level of serum creatinine in the blood |
| `serum_sodium` | Level of serum sodium in the blood |
| `sex` | Patient's biological sex |
| `smoking` | Whether the patient smokes (boolean) |
| `time` | Follow-up period (days) |
| `DEATH_EVENT` | Whether the patient deceased during follow-up |

---

## ⚙️ Technologies Used

| Tool | Purpose |
|------|---------|
| 🐍 Python | Core programming language |
| 📊 Pandas & NumPy | Data manipulation and analysis |
| 📉 Matplotlib & Seaborn | Data visualization |
| 📓 Jupyter Notebook | Interactive development environment |

---

## 📈 EDA Highlights

- ✅ Analyzed the **distribution of clinical features** such as age, ejection fraction, and serum creatinine
- ✅ Explored the **impact of high blood pressure** on heart failure outcomes
- ✅ Investigated **survival rates** across different patient demographics
- ✅ Identified and handled **outliers** in medical measurements
- ✅ Examined **correlations** between clinical variables using heatmaps
- ✅ Compared feature distributions across **death event (0 vs 1)** groups

---

## 🛠️ Feature Engineering Steps

- 🔄 Converted **boolean/binary features** into appropriate numerical formats
- 🧹 Handled **missing values** using domain-informed strategies
- 📏 Applied **scaling and normalization** to continuous clinical variables
- 🧪 Created **derived features** to capture interaction effects between clinical markers
- 🗂️ Encoded and transformed **categorical variables** for model readiness
- 📊 Performed **feature importance analysis** to identify top predictors

---

## 🖼️ Visualizations

### 📊 Histogram of High Blood Pressure

This histogram illustrates the distribution of high blood pressure among patients in the dataset, providing a clear view of how hypertension is distributed across the clinical records.

![Histogram of High Blood Pressure](https://raw.githubusercontent.com/AbhishekDhawan07/EDA_and_Feature_Engineering_Project_on_Heart_Failure_Dataset/main/Histogram%20of%20High%20Blood%20Pressure.png)

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AbhishekDhawan07/EDA_and_Feature_Engineering_Project_on_Heart_Failure_Dataset.git
   ```

2. **Navigate to the project folder:**
   ```bash
   cd "EDA and Feature Engineering Project on Heart Failure Dataset"
   ```

3. **Install required dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. **Launch the Jupyter Notebook:**
   ```bash
   jupyter notebook "EDA and Feature Engineering on Heart Failure Dataset.ipynb"
   ```

5. **Run all cells** to reproduce the full analysis and visualizations.

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature-name`)
5. Open a Pull Request

---

## 📄 License

This project is open-source and available for educational and research purposes.

---

<div align="center">

⭐ **If you found this project helpful, please give it a star!** ⭐

Made with ❤️ by [Abhishek Dhawan](https://github.com/AbhishekDhawan07)

</div>
