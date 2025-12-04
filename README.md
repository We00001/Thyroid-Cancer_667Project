# Self-Assessment vs. Clinical-Assessment Models for Thyroid Cancer

## Authors

-   Dan Huang
-   Yuchen Li
-   Zhenzhong Zhang
-   Evan Rhodes

## Data
The analysis uses the "Multi-Visit Thyroid Cancer Monitoring Dataset" available on Kaggle.

-   **Dataset Website:** [https://www.kaggle.com/datasets/datasetengineer/multi-visit-thyroid-cancer-monitoring-dataset-shd](https://www.kaggle.com/datasets/datasetengineer/multi-visit-thyroid-cancer-monitoring-dataset-shd)

The `Final_Report.qmd` document is designed to automatically handle the data download and setup. When you render the report, the script will:
1.  Check if the data file exists in the `data/` directory.
2.  If the data is not found, it will attempt to download the dataset from Kaggle and unzip it into the `data/` directory.
