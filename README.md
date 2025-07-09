# Real Estate Data Processing Pipeline

## Project Description
This project is a Python-based data processing pipeline for real estate market analysis. It ingests, cleans, transforms, and explores real estate data, providing insights such as property type distributions, average prices, and more. The pipeline is built using object-oriented programming principles for modularity and maintainability.

The application demonstrates:
- How to encapsulate data operations in a class (`RealEstateDataset`)
- Data ingestion, cleaning (handling missing/invalid values), and basic exploratory analysis
- Feature engineering and advanced visualization
- Use of pandas, numpy, matplotlib, and seaborn for efficient data manipulation and visualization

**Why these technologies?**
- **Python** is widely used for data science and scripting.
- **pandas** and **numpy** are industry standards for data analysis and numerical operations.
- **matplotlib** and **seaborn** are popular for data visualization.
- **Jupyter Notebook** allows for interactive, step-by-step data exploration and visualization.

**Challenges faced:**
- Ensuring robust handling of missing and invalid data
- Designing a flexible class structure for future extensibility

---

## Directory Structure

```
Real_Estate_Data_Processing_Pipeline/
│
├── data_ingestion.ipynb         # Notebook for data loading, cleaning, and basic exploration
├── data_transformation.ipynb    # Notebook for feature engineering and visualization
├── requirements.txt             # Project dependencies
├── README.md                    # Project documentation
└── data/
    ├── housing_data.csv         # Raw real estate dataset
    └── cleaned_housing_data.csv # Cleaned dataset after processing
```

---

## How to Run the Project

1. **Install requirements:**
   ```bash
   pip install -r requirements.txt
   ```
2. **Run the notebooks to see the results (in order):**
   - First, open and execute `data_ingestion.ipynb` in Jupyter Notebook to load, clean, and save the data.
   - Then, open and execute `data_transformation.ipynb` in Jupyter Notebook to perform feature engineering and visualization.

---

## Features

- **Data Ingestion:** Robust loading and preview of real estate data.
- **Data Cleaning:** Handles missing values, negative values, and categorical/date cleaning.
- **Exploratory Analysis:** Summary statistics, property type distribution, price/size by group.
- **Feature Engineering:** Adds price per square foot and property age.
- **Visualization:** Price distribution, top locations, and price trends over time.

---

## About Me

I'm a data enthusiast passionate about transforming raw data into meaningful insights. With hands-on experience in data engineering, data science and analytics. I enjoy building scalable pipelines, designing efficient data models and uncovering patterns through advanced SQL and statistical techniques.

<p align="left">
  <a href="https://linkedin.com/in/supritspatil" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://www.supritpatil.co/" target="_blank">
    <img src="https://img.shields.io/badge/Website-FF6F00?style=for-the-badge&logo=Google-Chrome&logoColor=white" alt="Website"/>
  </a>
  <a href="https://github.com/ssp964" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-24292E?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>