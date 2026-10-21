# Hotel Bookings Exploratory Data Analysis (EDA)

**A Python data analysis project exploring hotel booking patterns, customer behavior, and cancellations.**

## Project Overview

This project performs Exploratory Data Analysis (EDA) on hotel booking data for City Hotels and Resort Hotels. The objective is to understand booking trends, identify data quality issues, explore relationships between variables, and extract meaningful business insights through data visualization.

## Objectives

- Understand the dataset structure and its data quality.
- Identify and handle duplicate records and missing values.
- Clean inconsistent and invalid data where appropriate.
- Analyze categorical and numerical variables.
- Explore factors associated with booking cancellations.
- Visualize distributions, outliers, and relationships between variables.
- Summarize meaningful insights from the analysis.

## Dataset

- **Dataset name:** Hotel Booking Demand
- **Source:** [Hotel Booking Demand — Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
- **Original dataset size:** 119,390 rows and 32 columns.

The dataset contains information about hotel reservations, including hotel type, lead time, length of stay, customer type, market segment, average daily rate, special requests, and reservation status.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## Project Workflow

1. Loaded and inspected the dataset.
2. Examined dataset dimensions, data types, and descriptive statistics.
3. Identified and removed duplicate records where appropriate.
4. Investigated and handled missing values.
5. Cleaned data types, categorical values, and invalid records.
6. Performed univariate analysis.
7. Performed bivariate and multivariate analysis.
8. Visualized distributions, outliers, and correlations.
9. Summarized important findings and conclusions.

## Key Findings

- City Hotels account for more bookings than Resort Hotels in the analyzed dataset.
- Approximately 27.5% of bookings were canceled in the original analysis.
- Lead time and average daily rate show variation across bookings.
- Cancellation rates differ between hotel types and customer groups.
- Bookings with more special requests showed lower cancellation rates in the analysis. This is an observed association and does not establish causation.

## Repository Structure

- `notebooks/` — Jupyter notebook containing the complete analysis.
- `data/` — Dataset, if included and permitted by its license.
- `requirements.txt` — Required Python libraries.
- `README.md` — Project documentation.

## How to Run the Project

1. Clone or download this repository.
2. Install the required libraries using:

   `pip install -r requirements.txt`

3. Download the dataset from the Kaggle link above if it is not included.
4. Place the CSV file in the expected location or update the file path in the notebook.
5. Open the notebook in Google Colab or Jupyter Notebook.
6. Run the cells from top to bottom.

## Conclusion

This project demonstrates practical skills in data cleaning, exploratory data analysis, data visualization, and interpretation of real-world data. The findings provide a foundation for further analysis and potential future machine learning tasks, such as predicting booking cancellations.

## Author

**HEMANTH SAI CHATHARASI**
