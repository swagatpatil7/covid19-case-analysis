# COVID-19 Early Case Trend Analysis & Recovery Insights

An exploratory data analysis (EDA) project on a patient-level COVID-19 dataset,
built as part of an AI/ML internship minor project.

## 📌 Objective

Analyze early-stage COVID-19 case data to uncover:
- Demographic patterns (age, gender, region)
- Infection spread patterns (source, order, exposure)
- Recovery timelines and influencing factors
- Regional case concentration

## 🗂️ Dataset

Patient-level records with attributes including:
`sex`, `birth_year`, `country`, `region`, `infection_reason`,
`infection_order`, `contact_number`, `confirmed_date`,
`released_date`, `deceased_date`, `state`

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn

## 📊 Analysis Performed

- Data cleaning and preprocessing
- Feature engineering: `age` from `birth_year`, `recovery_days` from date columns
- Visualizations: gender distribution, age distribution, regional case map,
  infection reasons, case outcome distribution, recovery timelines
- Correlation analysis
- Linear Regression to predict recovery duration (optional extension)

## 🚀 How to Run

1. Clone the repo
2. Open `covid19_analysis.ipynb` in Jupyter or Google Colab
3. Upload the dataset CSV
4. Run all cells

## 👤 Author

Swagat Patil
