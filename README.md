# Exploratory-Data-Anaylsis-using-Python-
Exploratory Data Analysis (EDA) on a Superstore Dataset

Table of Contents

1. Project Overview
2. Dataset Information
3. Project Structure
4. Installation and Setup
5. Analysis Overview
6. Key Insights
7. Usage
8. Dependencies
9. Contributing
10. License

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a **Superstore Sales Dataset** using Python. EDA is a crucial step in understanding the underlying structure of the dataset, identifying patterns, spotting anomalies, checking assumptions, and testing hypotheses with the help of summary statistics and graphical representations.

The purpose of this project is to gain insights into various business metrics such as **sales**, **profit**, **customer segmentation**, and **regional performance**, which will help the store management in making informed decisions.

## Dataset Information

The dataset contains sales records from a superstore, including features like:

- **Order ID:** Unique ID for each order
- **Customer ID:** Unique ID for each customer
- **Segment:** Customer segment (Consumer, Corporate, or Home Office)
- **Country, Region, and City:** Location details of the sales
- **Category and Sub-Category:** The type of products sold
- **Sales, Quantity, Discount, Profit:** Sales metrics for each order

> Note: The dataset is assumed to be in a CSV format, but it can be modified according to the source.

## Project Structure


## Installation and Setup

To run the project locally, follow these steps:

1. Clone the repository:
  
   
2. Navigate to the project directory:
   
   
3. Install the required dependencies:
  

4. (Optional) Launch the Jupyter Notebook for interactive analysis:
  
## Analysis Overview

The EDA is conducted in multiple phases:

1. **Data Cleaning:**
   - Handling missing values, if any.
   - Converting data types to appropriate formats.
   - Removing or correcting any inconsistencies.

2. **Univariate Analysis:**
   - Analysis of individual columns like sales, profit, category, etc.
   - Distribution plots and summary statistics.

3. **Bivariate and Multivariate Analysis:**
   - Relationships between features (e.g., Sales vs. Cateogory, Sales  vs. Region).
   - Correlation matrix.
   - Grouping and aggregating data for deeper insights.

4. **Time Series Analysis:**
   - Investigating sales trends over time.

5. **Segmented Analysis:**
   - Analysis of customer segments, regions, and product categories.

6. **Visualization:**
   -Pie charts, bar charts 

## Key Insights

Some of the potential insights that can be obtained through this analysis are:

- **Top-performing products and categories** based on sales and profit.
- **Geographic distribution** of sales and profits.
- **Impact of discounts** on sales and profit.
- **Customer segmentation** analysis (Consumer, Corporate, Home Office).
- **Sales trends** over time.

> Detailed analysis results are available in the Jupyter Notebook (`EDA_Superstore.ipynb`) and summarized in the `eda_report.pdf`.

## Usage

1. Ensure the dataset is placed in the `data/` directory.
2. Run the Jupyter Notebook or use the Python scripts provided in the `src/` folder to reproduce the analysis.
3. You can customize the analysis by modifying the functions in `src/analysis.py` or adding new visualizations in `src/visualization.py`.

## Dependencies

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib

To install dependencies, run:
```bash
pip install -r requirements.txt
```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a new Pull Request



