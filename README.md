# Similar Table Search on PubTables-1M

---

## Description
This notebook implements a system for analyzing and searching for similar tables in the **PubTables-1M** dataset. It uses XML to extract structural features of tables, JSON to extract content features of tables and search for similarity with FAISS. Clustering is also done for the analysis of outliers.

## Features
- Loading XML files containing tables. Loading JSON files containing tables.
- Extracting structural features (number of rows, columns, spanning cell, column header and projected row header) and content features (percent letters, percent numbers, percent symbols).
- Analyzing and comparing tables to identify similarities with FAISS and Clustering.

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
1. Load the **PubTables-1M** dataset (than modify the code and the directory to reference to it).
2. Run the cells to extract table features.
3. Analyze the results to identify similar tables.

## Directory
The data folder structure should look like this:
```none
Find_similar_tables_on_PubTables-1M
├── ...
├── es tabella e XML corrispondente
├── Primi20_PubTables
├── PubTables-1M
│   ├── images
│   │   ├── tablename.jpg
│   │   ├── ...
│   ├── test
│   │   ├── tablename.XML
│   │   ├── ...
│   ├── train
│   │   ├── tablename.XML
│   │   ├── ...
│   ├── val
│   │   ├── tablename.XML
│   │   ├── ...
│   ├── words
│   │   ├── tablename.JSON
│   │   ├── ...
```

## Author
This project was developed to analyze the structure of tables in the PubTables-1M dataset. If you have any suggestions or questions, feel free to contribute!
