***

# Customer Segmentation Python Notebook

***

## Project Purpose

**This notebook (`Customer_Segmentation.ipynb`) provides all the Python code for customer segmentation, retention analysis, and actionable business insights.**

***

## How to Use the Notebook

### 1. Open the Notebook

- **Google Colab (recommended for interactive charts):**  
  **  
  Download and run with Anaconda/Jupyter.

***

### 2. Supply Your Data

- Upload your CSV file, e.g. `online.csv`.
- **Required columns:**  
  - `Invoice`
  - `Customer ID`
  - `Date`
  - `Amount`
  - `Product`

***

### 3. Install Requirements

```bash
pip install pandas numpy plotly scikit-learn
```
Or use:  
```bash
pip install -r requirements.txt
```

***

### 4. Run All Cells

- Execute from top to bottom for analysis and visuals.

***

## Main Features

- **Data Cleaning**: Handles missing values, type conversions, duplicates.
- **EDA**: Summary stats and initial exploration.
- **RFM Segmentation**: Groups customers by Recency, Frequency, Monetary value.
- **KMeans Clustering**: Automated group detection using machine learning.
- **Cohort Retention Analysis**: Reveals trends in retention and churn.
- **Product and Trend Insights**: Analyzes top-selling products and monthly patterns.
- **Business Recommendations**: Provides practical actions based on data insights.

***

## Outputs

- **Interactive charts**: Plotly visuals embedded in the notebook.
- **Tables and metrics**: Key results appear after cell execution.

***

## Example Usage

```python
import pandas as pd
df = pd.read_csv("online.csv")  # Use Colab upload or Drive path if needed
# Click "Runtime > Run all" or run cells sequentially
```

***

## Author

**Abdelrahman Mohamed Salem**  
_Data Analyst & Python Developer_

***

> *For dashboard visuals or full project documentation, see the relevant README in those folders.*

***
