📒 Customer_Segmentation.ipynb – Analysis Notebook
✨ Purpose
This notebook uses Python to clean data, analyze customer transactions, and generate powerful insights about customer segments and retention. All code for data processing, analysis, and interactive charts is included here.

🛠️ How to Use
1. Open Notebook

Recommended: Run on Google Colab for interactive Plotly charts

Upload your CSV file (e.g. online.csv).

Required columns: Invoice, Customer ID, Date, Amount, Product.

3. Install Required Libraries

python
pip install pandas numpy plotly scikit-learn
Or use the project's requirements.txt.

4. Run All Cells

Execute from top to bottom to get all outputs and charts.

🔍 What’s Inside
Data Cleaning: Fixes missing values, data types, and duplicates.

EDA: Key metrics and distributions.

RFM Analysis: Segments customers by Recency, Frequency, Monetary Value.

KMeans Clustering: Finds optimal customer groups automatically.

Cohort Analysis: Tracks retention and churn by join date.

Product & Trend Insights: Monthly and product sales analysis.

Business Recommendations: Highlights actionable strategies.

📊 Output
Interactive charts and tables appear in the notebook cells after you run them.

Save your work with all cell outputs for easy sharing/viewing via GitHub or Colab.

🗃️ Sample Usage
python
import pandas as pd
df = pd.read_csv("online.csv")  # change path if using Drive
# Run cells from top or click "Runtime > Run All"
👨‍💻 Author
Notebook by Abdelrahman Mohamed Salem
For analytics learning, freelance, and business improvement.

Tip:
Use this notebook as a base for your own segmentation, clustering, or retention case studies.

(For dashboard and project-wide info, see their dedicated README files!)
