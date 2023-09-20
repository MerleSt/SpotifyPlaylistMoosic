**Spotify Playlist**

The Task: You have a CSV file with audio features of 5000 songs taken from Spotify. Create playlists with at least 50 and at most 250 songs, whose features are as simliar as possible.

As you can see this project displayls a clustering problem, which can be solved using usupervised machine learning, since there are no pre defined clusters. Beneath you can see the outline of my work. I will take you through it, step by step. Further comments are provided in the notebooks itself.

As you can see in the notebooks folder, there are two notebooks, one in which I clean the data, and one in which I make the actual analysis. In the Data folder you can see the data used in this project, once the original file and once the cleaned and ready to use for analysis file.

Your project should now have three main parts:

1. Data preparation:
- Reading the data
- Initial quick exploration
- Dropping unwanted features
2. Modelling:
- Data scaling (potentially, other transformations)
- K-Means exploration of clusters (elbow method, silhouette coefficient…)
- K-Means final model
3. Cluster exploration:
- Univariate and bivariate exploration of the clusters
- Manual labelling of the clusters
