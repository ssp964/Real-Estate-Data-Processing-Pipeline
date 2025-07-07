# Real Estate Data Processing Pipeline

## Project Description
This project is a Python-based data processing pipeline for real estate market analysis. It ingests, cleans, and explores real estate data, providing insights such as property type distributions, average prices, and more. The pipeline is built using object-oriented programming principles for modularity and maintainability.

The application demonstrates:
- How to encapsulate data operations in a class (`RealEstateDataset`)
- Data ingestion, cleaning (handling missing/invalid values), and basic exploratory analysis
- Use of pandas and numpy for efficient data manipulation

**Why these technologies?**
- **Python** is widely used for data science and scripting.
- **pandas** and **numpy** are industry standards for data analysis and numerical operations.
- **Jupyter Notebook** allows for interactive, step-by-step data exploration and visualization.

**Challenges faced:**
- Ensuring robust handling of missing and invalid data
- Designing a flexible class structure for future extensibility

---

## How to Install and Run the Project

1. **Clone the repository** and ensure you have the required dataset (CSV file) in the `data/` directory.
2. **Install dependencies:**
   ```bash
   pip install pandas numpy
   ```
3. **Open `data_pipeline.ipynb` in Jupyter Notebook.**
4. **Run the notebook cells in order:**
   - The first cell defines the `RealEstateDataset` class. Run this cell first.
   - In a new cell, create an instance and use the class methods as shown below:
     ```python
     file_path = 'data/housing_data.csv'
     r1 = RealEstateDataset()
     r1.load_data(file_path)
     r1.clean_data()
     r1.describe_data()
     # Save cleaned data
     r1.get_data().to_csv('data/cleaned_housing_data.csv', index=False)
     ```

**If you want to use the class in a separate Python script (.py file):**
- Move the class definition to a file named `data_pipeline.py`.
- Then, in your script, you can use:
  ```python
  from data_pipeline import RealEstateDataset
  # ...rest of the code as above
  ```

### Features
- **Data Ingestion:** Reads a CSV file and previews the first few rows.
- **Data Cleaning:**
  - Fills missing values in numerical columns with the mean
  - Fills missing values in categorical columns with 'Unknown'
  - Handles negative values in numerical columns by replacing them with the median
- **Exploratory Analysis:**
  - Prints mean, median, and mode for numerical columns
  - Shows distribution of property types
  - Calculates average prices by property type
  - Calculates average property size by location 

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