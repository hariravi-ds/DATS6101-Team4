# Rice Production Data

### Overview
This repository contains the dataset for the project titled **"Global Rice Production Analysis."** Predicting rice production outcomes is vital for global food security and agricultural sustainability. This dataset, “Explore Data on Agricultural Production,” includes approximately 13,500 rows and 40 columns, focusing on factors influencing rice yield, such as land area, climatic conditions, and waste generation.
We will conduct exploratory data analysis (EDA) to clean the dataset and examine the relationships among variables. By evaluating factors like soil quality, rainfall patterns, and agricultural practices, we aim to build predictive models to estimate rice yields. This study addresses real-world challenges in rice cultivation and provides insights to enhance agricultural strategies and promote sustainable practices, ultimately contributing to improved global food security.


### Dataset Details
- **Source**: https://ourworldindata.org/agricultural-production#explore-data-on-agricultural-production
- **Size**: 3.58MB
- **Format**: CSV
- **Number of Entries**: 13504
- **Number of Columns**: 40

### Usage
You can load the dataset into your Python environment using pandas as follows:
```python
import pandas as pd

data = pd.read_csv('Rice_Production_Data.csv')
