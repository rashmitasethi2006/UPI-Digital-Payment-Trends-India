

# UPI Growth and Digital Payment Trends in India (2016–2026)

## Project Overview

This project analyzes the growth and development of Unified Payments Interface (UPI) transactions in India from April 2016 to March 2026.

The analysis uses monthly UPI statistics published by the National Payments Corporation of India (NPCI). It explores transaction volume, transaction value, participating banks, yearly growth, and trends in digital payments.

The project also includes an interactive dashboard built using Plotly Dash to explore UPI trends across financial years.

## Objectives

- Analyze the growth of UPI transactions in India from 2016 to 2026.
- Study monthly and yearly trends in transaction volume and value.
- Examine the relationship between transaction volume and transaction value.
- Identify patterns, growth trends, and unusual observations.
- Develop an interactive dashboard for visual exploration.
- Present findings through data visualizations and analysis.

## Dataset

**Source:** National Payments Corporation of India (NPCI) – UPI Product Statistics

The dataset contains monthly UPI statistics covering April 2016 to March 2026.

### Main Features

| Feature | Description |
|---|---|
| Month | Month and year of the reported statistics |
| Banks Live on UPI | Number of banks live on the UPI platform |
| Volume (Mn.) | Number of UPI transactions in millions |
| Value (Cr.) | Total transaction value in crore rupees |

The monthly Excel files are combined into a single dataset for analysis.

## Tools and Technologies

- **Python** – Data processing and analysis
- **Pandas** – Data cleaning and manipulation
- **NumPy** – Numerical operations
- **Matplotlib and Seaborn** – Data visualization
- **Plotly** – Interactive charts
- **Dash** – Interactive dashboard
- **Jupyter Notebook / Google Colab** – Development environment
- **GitHub** – Project version control and hosting

## Project Workflow

1. Collect monthly UPI statistics from NPCI.
2. Combine the Excel files into one dataset.
3. Clean and prepare the data.
4. Convert date and numeric columns into appropriate formats.
5. Create additional features such as average transaction value and growth percentage.
6. Perform exploratory data analysis.
7. Generate visualizations to understand transaction trends.
8. Build an interactive dashboard using Plotly Dash.
9. Interpret the results and summarize key findings.

## Visualizations

The project includes the following visualizations:

- Monthly UPI transaction volume trend
- Yearly transaction volume comparison
- Monthly transaction value trend
- Correlation heatmap
- Transaction volume and value scatter plot
- Transaction volume box plot
- Yearly transaction value analysis

Each visualization helps explain a different aspect of UPI growth and digital payment activity.

## Interactive Dashboard

The Plotly Dash dashboard provides:

- Financial-year selection
- Interactive monthly transaction volume chart
- Interactive monthly transaction value chart
- Dynamic updates based on the selected financial year

The dashboard is implemented in `app.py`.

## Repository Structure

```text
upi-digital-payment-trends-india/
│
├── UPI_Growth_Analysis.ipynb
├── app.py
├── README.md
├── requirements.txt
│
├── data/
│   └── README.md
│
└── reports/
    ├── monthly_volume.png
    ├── yearly_volume.png
    ├── monthly_value.png
    ├── correlation_heatmap.png
    └── volume_value_scatter.png
```

*Note: Add the actual dataset files and chart images to the folders. Update the filenames in this structure if your files have different names.*

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/rashmitasethi2006/UPI-Digital-Payment-Trends-India.git
cd UPI-Digital-Payment-Trends-India
```

### 2. Install the required libraries

```bash
pip install -r requirements.txt
```

### 3. Run the analysis notebook

Open `UPI_Growth_Analysis.ipynb` in Jupyter Notebook or Google Colab and run the cells in order.

### 4. Run the dashboard

Make sure the required dataset files are available in the location specified in `app.py`, then run:

```bash
python app.py
```

Open the local URL shown in the terminal to view the dashboard.

## Key Findings

The analysis examines the growth of UPI transaction volume and value over the study period, changes across financial years, and the relationship between transaction volume and transaction value.

The detailed findings and interpretations are available in the analysis notebook and project report.

## Limitations

- The analysis depends on the accuracy and availability of the published NPCI data.
- The dataset contains monthly aggregate statistics and does not include individual transaction details.
- The project describes historical trends and does not establish the causes of every observed change.
- Future transaction trends may differ from the historical patterns.

## Future Scope

- Extend the analysis with additional digital payment datasets.
- Add forecasting models to estimate future UPI transaction trends.
- Include more dashboard filters and visualizations.
- Deploy the dashboard online for public access.
- Compare UPI with other digital payment methods.

## Use of AI Tools

AI tools were used to support understanding of the dataset, coding assistance, debugging, and interpretation of analytical outputs. The project code and findings were reviewed against the actual dataset and generated results.

## Conclusion

This project provides an overview of UPI growth and digital payment trends in India from 2016 to 2026 using monthly NPCI statistics. Through data cleaning, exploratory analysis, visualization, and an interactive dashboard, it presents the development of UPI transaction volume and value over time.

## References

- National Payments Corporation of India (NPCI): https://www.npci.org.in/
- NPCI UPI Product Statistics: https://www.npci.org.in/what-we-do/upi/product-statistics

