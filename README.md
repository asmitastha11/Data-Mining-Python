# Data Mining with Python

A comprehensive collection of data mining implementations using Python and Jupyter Notebook. This project covers data preprocessing, exploratory data analysis, classification, association rule mining, clustering, web mining, text analysis, and database creation.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white" alt="Jupyter" />
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-green?logo=scikit-learn&logoColor=white" alt="Scikit-learn" />
  <img src="https://img.shields.io/badge/Pandas-DataFrame-150458?logo=pandas&logoColor=white" alt="Pandas" />
</p>

---

## Overview

This project demonstrates practical implementations of major data mining techniques in Python, including:

- Data preprocessing and exploratory data analysis
- Decision tree classification
- Rule-based classification
- K-nearest neighbour classification
- Naive Bayes classification
- Association rule mining with Apriori
- K-Means clustering
- Hierarchical clustering
- Web mining for text and structured data extraction
- Database creation and storage using SQLite

---

## Topics Covered

### Data Preprocessing and Exploratory Data Analysis

- Missing-value handling
- Categorical encoding
- Feature normalization
- Statistical exploration
- Data visualization
- Correlation analysis

### Classification

- Decision Trees
- Rule-based classification
- K-Nearest Neighbour
- Naive Bayes
- Train/test splitting
- Accuracy evaluation
- Classification reports
- Confusion matrices

### Association Rule Mining

- Transaction encoding
- Frequent itemset generation
- Apriori algorithm
- Support
- Confidence
- Lift

### Clustering

- K-Means clustering
- Elbow method
- Centroid analysis
- Agglomerative hierarchical clustering
- Dendrogram visualization
- Linkage methods

### Web Mining

- HTTP requests
- HTML parsing
- Web scraping
- Text cleaning
- Word-frequency analysis
- DataFrame creation
- SQLite database creation
- SQL-based data analysis

---

## Technologies and Libraries

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- MLxtend
- Requests
- BeautifulSoup4
- NLTK
- SQLAlchemy
- SQLite

---

## Project Structure

```text
data-mining-python/
│
├── notebooks/
│   ├── 01_data_preprocessing_eda.ipynb
│   ├── 02_decision_tree_classification.ipynb
│   ├── 03_rule_based_classification.ipynb
│   ├── 04_knn_classification.ipynb
│   ├── 05_naive_bayes_classification.ipynb
│   ├── 06_apriori_association_rules.ipynb
│   ├── 07_kmeans_clustering.ipynb
│   ├── 08_hierarchical_clustering.ipynb
│   ├── 09_web_mining_text_analysis.ipynb
│   └── 10_web_mining_database.ipynb
│
├── datasets/
├── .gitignore
├── requirements.txt
├── README.md
└── .venv/
```

---

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/data-mining-python.git
cd data-mining-python
```

### 2. Create a virtual environment

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### macOS/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Open the `notebooks/` directory and run the notebooks in order.

---

## Datasets

The implementations use datasets appropriate to the respective techniques, including:

- Titanic
- Iris
- Breast Cancer
- Wine
- Transactional / market-basket data
- Web-scraped text data

---

## Database

The web-mining database implementation uses SQLite through SQLAlchemy. The database file is generated locally when the corresponding notebook is executed and is excluded from Git using `.gitignore`.

---

## Main Concepts Demonstrated

### Data Preprocessing and EDA

- Missing-value handling
- Categorical encoding
- Feature normalization
- Statistical exploration
- Data visualization
- Correlation analysis

### Classification

- Decision Trees
- Rule-based classification
- K-Nearest Neighbour
- Naive Bayes
- Train/test splitting
- Accuracy evaluation
- Classification reports
- Confusion matrices

### Association Rule Mining

- Transaction encoding
- Frequent itemset generation
- Apriori algorithm
- Support
- Confidence
- Lift

### Clustering

- K-Means clustering
- Elbow method
- Centroid analysis
- Agglomerative hierarchical clustering
- Dendrogram visualization
- Linkage methods

### Web Mining

- HTTP requests
- HTML parsing
- Web scraping
- Text cleaning
- Word-frequency analysis
- DataFrame creation
- SQLite database creation
- SQL-based data analysis

---

## Notes

- Run the notebooks from the project root or adjust file paths as needed.
- Internet access is required for the web-mining notebooks.
- Generated databases, virtual environments, cache files, and other local files are excluded through `.gitignore`.
- Some datasets may be downloaded automatically by scikit-learn or fetched from the web during execution.

---

## Author

Asmita Shrestha

---

## License

This project is intended for educational and learning purposes.

---

<p align="center">
  <sub>Made with Python and Jupyter Notebook for learning and experimentation.</sub>
</p>
