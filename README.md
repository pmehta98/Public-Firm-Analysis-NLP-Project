# Public Firm Analysis: Industry Sector Report and NLP Analysis

This repository contains all the deliverables and resources for the BAIT 508 group project focused on conducting an in-depth analysis of public U.S. firms within the selected "Health Services" industry sector. The analysis combines quantitative financial data analysis (1994–2020), text-based natural language processing (NLP) insights from 10-K reports, and strategic recommendations based on competitor and historical analysis.

The objectives of this project are to provide a detailed analysis of the health services industry, utilize quantitative methods to identify trends and key financial behaviors, apply NLP techniques to extract insights from textual data, and offer actionable strategic suggestions for one sample firm (Tenet Healthcare Corporation).

### Files in the Repository
- **Project Ask Document** (`BAIT508 Group Project - Public Firm Analysis.docx`): Contains the project overview, goals, and detailed instructions.
- **Final Report** (`BAIT508_BA1_Group_9_Industry_Analysis_Report.pdf`): Includes the findings, visualizations, and strategic recommendations.
- **Jupyter Notebook** (`BAIT508_BA1_Group_9_Industry_Analysis_Report_Code.ipynb`): Contains the Python code used for data cleaning, analysis, and visualization.

The analysis utilized the following datasets:
1. **major_groups.csv**: SIC codes and industry descriptions.
2. **public_firms.csv**: Financial data of public firms (1994–2020).
3. **2020_10K_item1_full.csv**: Item 1 content from 10-K reports for 2020.

The methodology includes quantitative analysis to identify key industry trends, preliminary analysis of stock prices, sales, and geographical distributions, text analysis using word counts and TF-IDF scores, and Word2Vec modeling to identify industry-specific terms. The project also features a comprehensive analysis of Tenet Healthcare Corporation, comparing it with competitors and providing strategic suggestions based on key findings.

Key findings include insights into industry trends, operational inefficiencies in Tenet Healthcare Corporation, and recommendations for improvements in cost optimization, digital transformation, and compliance.

Technologies and tools used include Python and libraries such as `pandas`, `numpy`, `matplotlib`, `seaborn`, `nltk`, `gensim`, `sklearn`, and `wordcloud`.

To run the project:
1. Clone this repository using `git clone https://github.com/your-username/Public-Firm-Analysis-NLP-Project.git`.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter notebook to explore and replicate the analyses.

This project was completed as part of the **BAIT 508** course at UBC. Team members include Zhi (Krystal) Li, Yousef Jafarnia, and Pranav Mehta.

This project is licensed under the MIT License.
