# Financial_Analysis_Tool
# Financial Analysis of Forbes Global Companies (2022)

## Authors:
- **Kavya Kulkarni**  
  *Principle of Business Analytics - BUA 500*  
  *International Technological University*  
  *Santa Clara, California, United States*  
  *Email: kulkarnikavya6161@students.itu.edu*  

- **Nathaly Cobo Piza**  
  *Principle of Business Analytics - BUA 500*  
  *International Technological University*  
  *Santa Clara, California, United States*  
  *Email: cobopizanathaly1190@students.itu.edu*  

---

## Abstract

This analysis explores the dataset from Kaggle regarding the *Forbes Global Top 2000 Companies (2022)*. The dataset includes financial metrics such as **sales, profits, assets, and market value**. Python (Jupyter Notebook) was used to analyze and visualize data using **histograms, pie charts, and bar charts**. The goal is to understand the reasons behind the rankings of these companies.

**Keywords**: Data Analytics, Python, Forbes 2000, Financial Ratios

---

## Methodology

### Data Set

The dataset includes **the top 2000 largest companies in the world (2022)**, ranked based on:
- **Sales**
- **Profits**
- **Assets**
- **Market Value**

The dataset uses financial data from **April 2022**.

### Data Analytics Strategy

Following the **Data Analytics Life Cycle**, we structured our approach as follows:

1. **Define Objective**: Gain insights from the dataset.
2. **Understand Data**: Analyzed financial metrics.
3. **Data Cleaning & Transformation**:
   - Used **Pandas** to clean data.
   - Removed symbols (dollar signs, commas).
   - Converted data types.
4. **Enhancing Data**:
   - Added financial key ratios:
     - **Profit Margin** = `(profit / sales) * 100`
     - **Price-to-Sales Ratio (P/S)** = `market value / sales`
     - **Return on Assets (ROA)** = `(profit / assets) * 100`
5. **Data Visualization & Analysis**:
   - Used **Matplotlib** to generate insights.

---

## Results

### 1. Top 10 Countries by Market Cap (Forbes 2000 - 2022)
- **United States** leads with **66.26%** market cap.
- **China** follows at **7.13%**.
- **Saudi Arabia** ranks third (**7%**), driven by its oil industry.
- Other countries include the UK, Switzerland, Japan, France, Germany, Canada, and Taiwan.

### 2. Top 20 Companies (Forbes 2000 - 2022)
- Leading companies include **Berkshire Hathaway, Apple, JP Morgan Chase, Microsoft, and Amazon**.

### 3. Bottom 20 Companies
- Companies at the lower end of the ranking.

### 4. Financial Ratios Comparison

#### **Technology Sector: Alphabet vs. Microsoft**
- **Microsoft** has a **higher profit margin (38.5%)** than **Alphabet (29.5%)**.
- **Microsoft**'s **P/S ratio** is higher, indicating higher market valuation.
- **Both have high ROA** (~21%), showing strong asset utilization.

#### **Banking Sector: JPMorgan Chase vs. Bank of America**
- **JPMorgan Chase** has a **higher profit margin**.
- **Both banks show similar return on assets (ROA)**.
- **Revenue growth is stable**, but market perception varies.

#### **Telecommunications: AT&T, Telefónica, China Telecom**
- **Telefónica** has the **highest profit margin & ROA**.
- **AT&T** has the **highest revenue** but **lower profitability**.
- **China Telecom** has the lowest profit margin.

---

## Conclusions

- The Forbes ranking lacks financial ratios like **Profit Margin, P/S Ratio, and ROA**, which are essential for **investment decisions**.
- A **comprehensive financial analysis** provides better insights than raw rankings.
- **Python** is an effective tool for **data analysis, visualization, and managing financial datasets**.

---

## References

1. Jas, R. "Forbes Global Companies in 2022". Kaggle. [Dataset](https://www.kaggle.com/datasets/ramjasmaurya/top-2000-forbes-global-companies-in-2022)
2. Contreras, I., Murphy, A. "2022 Forbes Global 2000". Forbes. [Article](https://www.forbes.com/sites/isabelcontreras/2022/05/12/inside-the-global-2000-sales-and-profits-of-the-worlds-largest-companies-recovered-as-economies-reopened/?sh=cf6a45f11410)
3. Sood, S. "Data Analytics Life Cycle". [Vokse Digital](https://www.voksedigital.com/data-analytics-life-cycle/)
4. Segal, T. "Profit Margin Defined". [Investopedia](https://www.investopedia.com/terms/p/profitmargin.asp)
5. Macclure, B. "How to Use Price-To-Sales Ratios to Value Stocks". [Investopedia](https://www.investopedia.com/articles/fundamental/03/032603.asp)
6. Hargravel, M. "Return on Assets (ROA): Formula and 'Good' ROA Defined". [Investopedia](https://www.investopedia.com/terms/r/returnonassets.asp)
7. Reiff, N. "How Microsoft Makes Money". [Investopedia](https://www.investopedia.com/how-microsoft-makes-money-4798809)

---

## Python Analysis File

The full data analysis using Python can be found in the attached file:

**BUA500-DataAnalyticsUsingPythonKavyaKandNathalyC.html**
