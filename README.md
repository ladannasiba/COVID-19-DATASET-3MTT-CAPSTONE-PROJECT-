# COVID-19-DATASET-3MTT-CAPSTONE-PROJECT-

# Predictive Modeling for COVID-19 in Public Health

This project focuses on analyzing historical COVID-19 data to predict trends, uncover actionable insights, and inform public health policies. The analysis includes data preparation, exploratory data analysis (EDA), predictive model development, and visualization of findings.

## Project Structure

The project comprises the following components:

1. **Technical Report**
   - A detailed report describing the data preparation, EDA, model development, evaluation, and insights.
   - Format: Microsoft Word (.docx)

2. **Presentation**
   - A slide deck summarizing the findings, key insights, and public health recommendations.
   - Format: Microsoft PowerPoint (.pptx)

3. **Code Files**
   - Python scripts for data cleaning, analysis, and visualization.

## Dataset

- **Source**: Kaggle COVID-19 Open Research Dataset (CORD-19)
- **File Used**: `covid_19_clean_complete.csv`
- **Key Features**: Date, Country/Region, Confirmed, Deaths, Recovered

## Steps

### 1. Data Preparation
- Addressed missing values and duplicates.
- Standardized formats for date and country names.
- Created derived features such as:
  - `Daily_Cases`: New cases reported each day.
  - `Mortality_Rate`: Deaths as a percentage of confirmed cases.

### 2. Exploratory Data Analysis (EDA)
- Uncovered trends in daily cases and mortality rates.
- Visualizations included:
  - Line plots for daily cases by country.
  - Correlation heatmap to identify relationships.

### 3. Model Development
- **Model**: Random Forest Regressor
- **Features Used**:
  - `Daily_Cases`
  - `Mortality_Rate`
- **Target Variable**: `Confirmed`
- **Evaluation Metric**: RMSE (Root Mean Square Error)

### 4. Findings and Recommendations
- Mortality rates and daily case growth are significant predictors of trends.
- Recommendations include focusing on high-growth regions for resource allocation and intervention.

## Outputs

1. [Technical Report](./COVID19_Technical_Report.docx)
2. [Presentation](./COVID19_Presentation.pptx)

## How to Use

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Open the Jupyter Notebook or Python script to reproduce the analysis.
3. Use the outputs (report and presentation) for documentation and presentation purposes.

## Tools and Libraries

- Python
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

## Contact

For further questions or collaboration opportunities, please contact:
- **Name**: Nasiba Muhammad Ladan
- **Email**: nasyladan72@gmail.com
