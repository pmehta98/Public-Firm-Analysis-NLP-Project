# 📊 Public Firm Industry Analysis

This repository contains an in-depth analysis of public U.S. firms within the **Health Services** industry sector. The project leverages **quantitative analysis**, **text-based natural language processing (NLP)**, and **word embeddings** to generate strategic insights into the industry and a specific firm, **Tenet Healthcare Corporation**.

---

## 📋 Project Overview

### **Objective**
- Conduct a comprehensive analysis of public firms in the **Health Services** industry.
- Generate actionable insights using financial and textual data for industry-wide and firm-specific strategy development.

### **Scope**
1. **Quantitative Analysis**:
   - Identify trends in financial performance across the sector.
   - Examine the impact of major economic events (e.g., the 2008 financial crisis) on firms.
2. **Text Analysis**:
   - Perform keyword extraction and visualize key themes in 10-K reports using TF-IDF and word embedding techniques.
3. **Comprehensive Firm Analysis**:
   - Compare the financial and textual performance of **Tenet Healthcare Corporation** with its competitors.
   - Provide actionable strategic recommendations.

---

## 🔍 Key Insights & Recommendations

### **Industry-Wide Insights**
- **Top Firms by Sales**:
  - Firms like **HCA Healthcare Inc.**, **Tenet Healthcare Corp.**, and **Fresenius Medical Care AG** dominate sales in the health services sector.
- **Impact of 2008 Financial Crisis**:
  - The most affected firm in the sector was **Insight Health Services Holding**, with a **99.33% stock price drop**.
- **Trends**:
  - Average stock prices and ROA show a steady post-2008 recovery, indicating sector resilience.

### **Tenet Healthcare Corporation Analysis**
- **Strengths**:
  - High sales volume, reaching **$17 billion** in 2015.
- **Weaknesses**:
  - Stagnant stock price and ROA reflect operational inefficiencies.
- **Recommendations**:
  1. **Cost Optimization**:
     - Implement operational improvements and leverage digital solutions.
  2. **Investor Confidence**:
     - Enhance compliance and risk management to reduce legal setbacks.
  3. **Market Position**:
     - Focus on operational efficiency to convert sales into profits.

---

## 📂 Repository Contents

| File Name                               | Description                                                  |
|-----------------------------------------|--------------------------------------------------------------|
| **`BAIT508_BA1_Group_9_Industry_Analysis_Report.pdf`** | Comprehensive project report with detailed findings.         |
| **`BAIT508_BA1_Group_9_Industry_Analysis_Report_Code.ipynb`** | Jupyter Notebook with code for the analysis.                 |
| **`public_firms.csv`**                  | Financial data for public U.S. firms (1994-2020).            |
| **`major_groups.csv`**                  | Industry sector codes and descriptions.                      |
| **`2020_10K_item1_full.csv`**           | Text data from the 2020 10-K filings of public U.S. firms.   |

---

## 📊 Methodology

1. **Quantitative Analysis**:
   - Analyzed stock prices, sales, ROA, and geographical distribution of firms using **pandas** and **matplotlib**.
   - Examined the impact of the 2008 financial crisis and trends over time.
2. **Text Analysis**:
   - Cleaned textual data from 10-K reports using **NLTK**.
   - Extracted keywords using word counts and **TF-IDF**, visualized using word clouds.
   - Trained a **Word2Vec** model to explore word similarities.
3. **Comprehensive Analysis**:
   - Analyzed stock price, sales, and ROA trends for **Tenet Healthcare Corp.**.
   - Compared Tenet’s performance with competitors and identified key challenges.

---
