# Netflix Movies & TV Shows Clustering – Unsupervised Machine Learning

## Problem Statement
Can Netflix movies and TV shows be grouped into meaningful clusters based on their content characteristics, such as genre, description, cast, country, and content rating?

This project aims to apply unsupervised machine learning techniques to identify similarities between Netflix titles, discover content patterns, and explore how clustering can support content categorization and recommendation systems.

## Dataset
- **Source:** Kaggle – Netflix Movies and TV Shows Dataset
- **Dataset Size:** 7,787 rows × 12 columns
- **Format:** CSV
- **Features:** show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description.
- **Clustering Features:** type, listed_in, description, country, rating, and cast.

## Approach

### 1. Data Cleaning and Preprocessing
- Checked for missing and null values across all columns.
- Identified missing values in director, cast, country, date_added, and rating.
- Checked for duplicate records (no duplicate rows found).
- Handled missing categorical and text values.
- Prepared relevant features for machine learning.
- Standardized and transformed data where required.

### 2. Text Processing and Feature Engineering
- Combined relevant content attributes to create meaningful text features.
- Applied text preprocessing techniques.
- Removed common stopwords where applicable.
- Used TF-IDF (Term Frequency–Inverse Document Frequency) to convert textual information into numerical features.
- Prepared feature vectors for clustering.

### 3. Dimensionality Reduction
- Applied dimensionality reduction techniques, such as PCA, where appropriate.
- Reduced feature complexity to support visualization and cluster interpretation.

### 4. Clustering
- Applied an unsupervised clustering algorithm to group similar Netflix titles.
- Explored similarities based on genre, description, and other content attributes.
- Analyzed the resulting clusters to identify common themes and content patterns.

### 5. Optimal Cluster Selection
- Used the Elbow Method to evaluate different cluster counts.
- Used the Silhouette Score, if calculated, to assess cluster separation and cohesion.
- Selected the cluster configuration based on model evaluation results.

## Results and Findings

- Explored similarities among Netflix movies and TV shows using content-based features.
- Grouped titles into clusters based on their content characteristics.
- Identified common genres and themes within the resulting clusters.
- Investigated how unsupervised learning can organize large entertainment catalogues.
- Evaluated clustering performance using appropriate validation metrics.

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Project Objectives
- Understand the application of unsupervised machine learning.
- Perform text preprocessing and feature engineering.
- Apply TF-IDF for text-based feature extraction.
- Explore clustering algorithms for content grouping.
- Evaluate clustering performance and interpret results.
- Understand how clustering can support content discovery and recommendation systems.

## Conclusion
This project explores the application of unsupervised machine learning to the Netflix content catalogue. By processing textual and categorical features and applying clustering techniques, the analysis aims to identify similarities between movies and TV shows.

The project demonstrates practical skills in data preprocessing, feature engineering, text vectorization, dimensionality reduction, and unsupervised machine learning.


## Author
**Mayuri Laddha** · [LinkedIn](https://www.linkedin.com/in/mayuri-laddha-135938404) · [GitHub](https://github.com/Mayuriladdha)
## Author
**Mayuri Laddha** · [LinkedIn](https://www.linkedin.com/in/mayuri-laddha-135938404) · [GitHub](https://github.com/Mayuriladdha)
