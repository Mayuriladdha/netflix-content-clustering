# Netflix Movies & TV Shows Clustering (Unsupervised ML)

## Problem Statement
Can Netflix titles be grouped into meaningful clusters based on their content features, such as genre, description, cast, and country? This can support content recommendation and catalogue understanding.

## Dataset
- **Source:** [Kaggle / course dataset: add link]
- **Size:** [X] rows × [Y] columns
- **Features used:** [e.g. type, listed_in, description, country, rating]

## Approach
1. **Data cleaning:** handled [missing values in director/cast/country], removed [duplicates]
2. **Text processing:** [removed stopwords, applied TF-IDF vectorization on description/genre]
3. **Dimensionality reduction:** [PCA, if used]
4. **Clustering:** [K-Means / Hierarchical / DBSCAN]
5. **Choosing k:** [Elbow method and silhouette score: optimal clusters = N]

## Results
- Titles were grouped into **[N] clusters**
- Silhouette score: **[X.XX]** (remove this line if you didn't compute one)
- Cluster examples: [Cluster 1: e.g. family and kids content, Cluster 2: e.g. crime dramas]

## Charts
![Elbow curve](images/elbow.png)
![Cluster visualization](images/clusters.png)

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Notebook
📓 [View the notebook](PASTE-NBVIEWER-OR-GITHUB-LINK)

## Author
**Mayuri Laddha** · [LinkedIn](https://www.linkedin.com/in/mayuri-laddha-135938404) · [GitHub](https://github.com/Mayuriladdha)
