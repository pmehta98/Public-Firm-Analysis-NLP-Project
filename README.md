# 📊 Public Firm Industry Analysis - NLP Project

![GitHub last commit](https://img.shields.io/github/last-commit/pmehta98/Public-Firm-Analysis-NLP-Project)
![GitHub repo size](https://img.shields.io/github/repo-size/pmehta98/Public-Firm-Analysis-NLP-Project)
![GitHub stars](https://img.shields.io/github/stars/pmehta98/Public-Firm-Analysis-NLP-Project?style=social)

## 📋 Table of Contents
- [Overview](#overview)
- [Project Scope](#project-scope)
- [Key Findings](#key-findings)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Repository Structure](#repository-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 📌 Overview

This repository contains an in-depth analysis of public U.S. firms within the **Health Services** industry sector. The project leverages **quantitative analysis**, **text-based natural language processing (NLP)**, and **word embeddings** to generate strategic insights into the industry and a specific firm, **Tenet Healthcare Corporation**.

The analysis combines traditional financial metrics with advanced NLP techniques to provide a comprehensive view of industry dynamics, competitive positioning, and firm-specific performance.

---

## 🎯 Project Scope

### 📊 Quantitative Analysis

- Identify trends in financial performance across the Health Services sector
- Analyze key metrics: Revenue, ROA, stock price performance
- Examine the impact of major economic events (e.g., 2008 financial crisis)
- Compare industry leaders and identify market concentration

### 📝 Text Analysis (NLP)

- Extract keywords from 10-K reports using TF-IDF
- Visualize key themes and topics in regulatory filings
- Apply word embedding techniques for semantic analysis
- Compare textual patterns across firms
- Identify strategic focus areas through text mining

### 🏥 Comprehensive Firm Analysis - Tenet Healthcare

- Compare Tenet Healthcare's financial and textual performance with competitors
- Identify strengths, weaknesses, and strategic positioning
- Provide actionable recommendations for improvement
- Analyze MD&A sections for management sentiment

---

## 💡 Key Findings

### Industry-Wide Insights

#### Top Firms by Sales
- **HCA Healthcare Inc.**
- **Tenet Healthcare Corp.**
- **Fresenius Medical Care AG**
- Significant market concentration among top players

#### Impact of 2008 Financial Crisis
- **Most Affected Firm:** Insight Health Services Holding
  - **99.33% stock price drop** during crisis period
- **Sector Recovery:** Average stock prices and ROA showed steady post-2008 recovery
- **Industry Resilience:** Health services sector demonstrated strong fundamentals

#### Key Trends
- Post-crisis growth in average stock prices
- ROA stabilization across major firms
- Increasing focus on operational efficiency
- Digital transformation themes emerging in 10-K reports

### Tenet Healthcare Corporation Specific Analysis

#### Strengths
- **High Sales Volume:** Reached **$17 billion** in 2015
- Strong market presence in hospital operations
- Diversified healthcare services portfolio

#### Weaknesses
- **Stagnant Stock Price:** Limited investor confidence
- **Low ROA:** Operational inefficiencies impacting profitability
- Legal and compliance challenges affecting performance

#### Strategic Recommendations

1. **Cost Optimization**
   - Implement operational improvements
   - Leverage digital health solutions
   - Streamline administrative processes

2. **Investor Confidence**
   - Enhance compliance and risk management
   - Improve transparency in financial reporting
   - Address legal setbacks proactively

3. **Market Position**
   - Focus on converting sales into profits
   - Improve operational margins
   - Invest in high-value service lines

---

## ✨ Features

- **Multi-Modal Analysis:** Combines quantitative financial data with qualitative text analysis
- **NLP Techniques:** TF-IDF, word embeddings, topic modeling
- **Industry Benchmarking:** Comprehensive competitor analysis
- **Time Series Analysis:** Historical performance trends
- **Visualization:** Interactive charts and word clouds
- **Strategic Insights:** Actionable business recommendations

---

## 🛠️ Setup

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook
- NLTK and spaCy for NLP
- pandas, numpy for data analysis

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/pmehta98/Public-Firm-Analysis-NLP-Project.git
   cd Public-Firm-Analysis-NLP-Project
   ```

2. **Install required packages:**
   ```bash
   pip install pandas numpy matplotlib seaborn
   pip install nltk spacy wordcloud
   pip install scikit-learn gensim
   python -m spacy download en_core_web_sm
   ```

3. **Download NLTK data:**
   ```python
   import nltk
   nltk.download('stopwords')
   nltk.download('punkt')
   ```

---

## 📖 Usage

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook analysis.ipynb
   ```

2. Run cells sequentially to:
   - Load and preprocess financial data
   - Perform quantitative analysis
   - Extract text from 10-K reports
   - Apply NLP techniques
   - Generate visualizations
   - Review recommendations

3. Modify parameters to analyze different firms or time periods

---

## 📂 Repository Structure

```
Public-Firm-Analysis-NLP-Project/
│
├── data/
│   ├── financial_data.csv
│   └── 10k_texts/
│
├── notebooks/
│   ├── quantitative_analysis.ipynb
│   ├── nlp_analysis.ipynb
│   └── firm_comparison.ipynb
│
├── visualizations/
│   ├── word_clouds/
│   └── charts/
│
├── reports/
│   └── final_analysis.pdf
│
└── README.md
```

---

## 🔧 Technologies Used

### Programming & Analysis
- **Python:** Core programming language
- **Jupyter Notebook:** Interactive development environment

### Data Analysis
- **pandas:** Data manipulation and analysis
- **numpy:** Numerical computations
- **scipy:** Statistical analysis

### Natural Language Processing
- **NLTK:** Text preprocessing and analysis
- **spaCy:** Advanced NLP and entity recognition
- **gensim:** Topic modeling and word embeddings
- **scikit-learn:** TF-IDF and machine learning

### Visualization
- **matplotlib:** Static visualizations
- **seaborn:** Statistical data visualization
- **wordcloud:** Word cloud generation
- **plotly:** Interactive charts

### Data Sources
- **SEC EDGAR:** 10-K filings
- **Financial databases:** Stock prices and financial metrics

---

## 🤝 Contributing

Contributions are welcome! If you'd like to enhance the analysis or add new features:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/EnhancedAnalysis`)
3. Commit your changes (`git commit -m 'Add enhanced NLP analysis'`)
4. Push to the branch (`git push origin feature/EnhancedAnalysis`)
5. Open a Pull Request

---

## 📄 License

This repository is for educational and portfolio purposes. Financial data and 10-K filings are publicly available from SEC EDGAR.

---

## 📧 Contact

**Pranav Mehta**

- GitHub: [@pmehta98](https://github.com/pmehta98)
- Repository: [Public-Firm-Analysis-NLP-Project](https://github.com/pmehta98/Public-Firm-Analysis-NLP-Project)

---

⭐ If you find this repository helpful, please consider giving it a star!

---
