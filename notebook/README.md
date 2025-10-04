Customer Segmentation & Retention Analysis
This project uses Python and interactive dashboards to analyze customer behavior, identify important customer segments, explore retention patterns, and translate findings into actionable business strategies.

🚀 Overview
Goal: Segment customers, analyze retention and churn, and provide data-driven recommendations for business growth.

Key Steps:

Data cleaning and preparation

Exploratory data analysis (EDA)

RFM (Recency, Frequency, Monetary) segmentation

KMeans clustering for segment discovery

Cohort and retention analysis

Business insights and actionable recommendations

📒 How to Use
Open the Notebook

You can use Google Colab (recommended for interactive charts).

Or, download and run locally using Jupyter.

Prepare the Data

Add your transactions dataset (online.csv) with the expected columns (Invoice, Customer ID, Date, Amount, etc.).

For Colab: upload CSV from your computer or load from Google Drive.

Run All Cells

Make sure all dependencies are installed:

text
pandas
numpy
plotly
scikit-learn
Run the notebook from top to bottom for full analysis and visualization.

🗂️ Project Structure
notebook/Customer_Segmentation.ipynb – All code, full analysis (data cleaning, EDA, RFM, clustering, cohorts, charts)

dashboard/ – Interactive and PDF dashboards (see folder README for details)

data/ – Place your (or sample) datasets here (not provided in this public repo)

reports/ – Project report and dashboards as PDFs

requirements.txt – List of required Python packages

📊 Key Features
Data cleaning: Handles missing values, types, duplicates

RFM segmentation: Manual quantiles (Champions, Loyal, At Risk, Lost, etc.)

KMeans segmentation: Finds optimal clusters with scaling and elbow method

Cohort retention analysis: Visualizes retention heatmaps and churn

Top products and trends: Monthly and weekly sales, product insights

Interactive charts: Built with Plotly (run notebook or view dashboards)

Actionable recommendations: Translating analytics into strategy

📦 Requirements
Python 3.x

See requirements.txt for detailed package list

Install with:

text
pip install -r requirements.txt
⚡ Data
This project expects a transaction dataset in CSV format.

Typical columns: Invoice/Order ID, Customer ID, Date, Amount, Product.

If you do not have access to the original dataset, add your data with matching structure, or request a sample format.

📄 Output
All findings, plots, and insights appear in the notebook.

Dashboards and PDF reports are provided in the /dashboard/ and /reports/ folders.

🤝 Acknowledgments
Analysis and code by Abdelrahman Mohamed Salem.
Feel free to use, share, or build on this project with attribution.

📬 Contact
For feedback, questions, or freelance inquiries, open an issue or contact via GitHub.


