# Oasis Infobyte Data Analytics Internship Projects

This repository contains data analytics projects completed as part of the Oasis Infobyte internship. Each task is delivered as a Jupyter Notebook with its corresponding dataset, covering exploratory analysis, customer segmentation, and sentiment classification.

## Projects

| Task | Project | Highlights |
| --- | --- | --- |
| 1 | [Exploratory Data Analysis on Retail Sales](DataAnalytics_L1_EDARetailSales/) | Examines sales trends, customer demographics, product-category performance, correlations, and practical retail recommendations. |
| 2 | [Customer Segmentation](DataAnalytics_L1_CustomerSegmentation_Task2/) | Builds RFM (Recency, Frequency, Monetary) features and applies K-Means clustering to identify customer groups and engagement opportunities. |
| 4 | [Sentiment Analysis](DataAnalytics_L1_SentimentAnalysis/) | Classifies product reviews as positive, neutral, or negative using TF-IDF text features and a balanced Logistic Regression model. |

## Repository structure

```text
OIBSIP/
├── DataAnalytics_L1_EDARetailSales/
│   ├── DataAnalytics_L1_EDARetailSales_Task1.ipynb
│   └── retail_sales_dataset.csv
├── DataAnalytics_L1_CustomerSegmentation_Task2/
│   ├── DataAnalytics_L1_CustomerSegmentation_Task2.ipynb
│   └── data.csv
└── DataAnalytics_L1_SentimentAnalysis/
    ├── DataAnalytics_L1_SentimentAnalysis_Task4.ipynb
    └── Reviews.csv
```

## Tools and libraries

- Python
- Jupyter Notebook / Google Colab
- pandas and NumPy
- Matplotlib and Seaborn
- scikit-learn
- TextBlob (sentiment-analysis notebook)

## Running the notebooks

1. Clone the repository:

   ```bash
   git clone https://github.com/WHH-JULIET/OIBSIP.git
   cd OIBSIP
   ```

2. Install the required packages:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn textblob jupyter
   ```

3. Open the relevant notebook in Jupyter Notebook, JupyterLab, or Google Colab. Keep each dataset in the same folder as its notebook. If running a notebook locally, update any `/content/...` file paths to the matching local dataset filename.

## Key outcomes

- Identified monthly and quarterly retail-sales patterns, category performance, and customer-demographic trends.
- Created three RFM-based customer groups: high-value/loyal, moderate/regular, and at-risk/low-spending customers.
- Built a review-classification workflow that turns raw product feedback into actionable sentiment categories.

## Author

**Shreya**<br>
Oasis Infobyte Data Analytics Intern

---

This work is intended for learning and portfolio purposes.
