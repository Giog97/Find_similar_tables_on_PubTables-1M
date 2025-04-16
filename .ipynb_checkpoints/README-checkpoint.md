# Similar Table Search on PubTables-1M

---

## Description
This notebook implements a system for analyzing and searching for similar tables in the **PubTables-1M** dataset. It uses XML to extract structural features of tables and compares them based on specific metrics.

## Features
- Loading XML files containing tables.
- Extracting structural features (number of rows, columns, spanning cell, column header and projected row header).
- Analyzing and comparing tables to identify similarities.

## Requirements
Before running the notebook, make sure you have installed the following libraries:
```bash
pip install numpy
pip install seaborn
pip install matplotlib
pip install scikit-learn
pip install plotly
pip install faiss-cpu
```

## Usage
1. Load the **PubTables-1M** dataset (and modify the code to reference to it).
2. Run the cells to extract table features.
3. Analyze the results to identify similar tables.

## Author
This project was developed to analyze the structure of tables in the PubTables-1M dataset. If you have any suggestions or questions, feel free to contribute!
