# Google Colab Project Files

This repository contains Jupyter notebooks created and executed in Google Colab for various data analysis and machine learning projects. Each notebook is structured for easy understanding and can be run directly in Google Colab.

## Table of Contents

- [Project Overview](#project-overview)
- [How to Run in Google Colab](#how-to-run-in-google-colab)
- [Notebooks](#notebooks)
- [Dependencies](#dependencies)
- [License](#license)

## Project Overview

This repository includes project files focused on data manipulation, machine learning, and visualization, all executed in Google Colab. These projects demonstrate:
- Accessing and modifying Google Sheets data using pandas
- Building data visualizations
- Implementing machine learning models
- Data pre-processing and analysis

## How to Run in Google Colab

You can easily open any of the `.ipynb` notebook files in Google Colab using the following steps:

1. Navigate to the desired notebook in this repository.
2. Open the file and click on the "Open in Colab" badge or use the link below to directly open the file.

Alternatively, use the following method to open notebooks in Colab:
1. Copy the link to the notebook's raw file.
2. Open [Google Colab](https://colab.research.google.com/).
3. Click `File` > `Open notebook`.
4. Select the `GitHub` tab and paste the repository URL.

### Google Sheets Integration Example
```python
import pandas as pd

# Load CSV from Google Sheets
csv_url = 'https://docs.google.com/spreadsheets/d/1CuK-FHXJzyCAPH_kSGFzS2g9rXTSM9z3/export?format=csv&gid=1429269838'
df = pd.read_csv(csv_url)

# Display data
df.head()

