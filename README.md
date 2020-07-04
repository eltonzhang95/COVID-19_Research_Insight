# COVID-19 Research Insight
The COVID-19 pandemic has impacted the world since the beginning of 2020. Lots of researches has been done to minimize the impact of the pandemic to the society. This project aims at providing insights on tackling the pandemic by analyze research papers published over the years on different types of corona-virus.
### Dataset
Metadata: https://drive.google.com/file/d/1SiodX8xuXJ2M4YbYozpePXe6Vx0HDdeh/view?usp=sharing
### Data Cleaning
The raw data are not ready for analysis due to excessive noise. The following steps are required before any further action:
1. drop duplicates
2. drop Nan
3. convert abstract to lower case
4. remove stopwords
5. stem
### Feature Engineering
TF-IDF transformation is performed to generate features that are fed into ML models.
### Clustering
The purpose of clustering is to find the similarities between viruses, which might provide some insights. For this project, K-Means model is deployed to split the dataset into 5 clusters, which respect to the five different types of viruses. Both PCA and t-SNE dimensionality reduction methods are implemented.
### Exploratory Analysis
Exploratory analysis such as word cloud and dendrogram are conducted through out the project.
