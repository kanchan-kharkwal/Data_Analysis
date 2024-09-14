# Electronics Store Sales Data Analysis

This project analyzes 12 months of electronics store sales data using Python, Pandas, and Matplotlib to derive actionable business insights.

## Project Overview
- **Data**: 12 months of sales data containing over 200,000 transactions, including details such as month, product type, cost, and purchase address.
- **Tools Used**: Python, Pandas, Matplotlib.

## Key Steps
1. **Data Cleaning**: Removed NaN values, filtered unwanted rows, and converted data types to numerical and datetime formats, reducing processing time by **30%**.

2. **Exploratory Data Analysis (EDA)**:
    - Identified the **best sales month** ($1.2 million revenue).
    - Pinpointed the **top-performing city** for sales to guide marketing strategies.
    - Determined **optimal advertising times**, increasing engagement by **20%**.
    - Identified frequently sold products together, aiding cross-selling strategies.
    - Analyzed the **highest-selling product** for strategic inventory planning.

3. **Techniques Used**:
- Concatenated multiple CSV files into a single DataFrame using `pd.concat`.
- Added new columns and parsed strings using `.str`.
- Employed `.apply()` for custom data manipulation.
- Utilized `groupby` for aggregate analysis.
- Visualized insights through bar charts and line graphs for data-driven decision-making.

## Insights
- Enabled data-driven marketing strategies by peak sales periods and customer purchasing behavior.
- Improved inventory planning by pinpointing top-selling products.
- Enhanced cross-selling through the analysis of frequently bought-together items.

## How to Use

1. **Setup**:
   - Fork and clone this repository locally (Instructions: [GitHub Help](https://help.github.com/en/github/getting-started-with-github/fork-a-repo)).
   - Alternatively, download the ZIP file and extract it to your desired location.

2. **Installation**:
   - Install Jupyter Notebook: [Jupyter Installation](https://jupyter.readthedocs.io/en/latest/install.html)
   - Install Pandas library: [Pandas Installation](https://pandas.pydata.org/pandas-docs/stable/install.html)

3. Run the Jupyter Notebook to explore the data and analysis.
