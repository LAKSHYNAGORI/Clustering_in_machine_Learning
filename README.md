# Clustering_in_machine_Learning

from sklearn.cluster import KMeans
import numpy as np
X = np.array([[1,2],[1,4],[1,0],[10,2]])
kmeans = KMeans(n_clusters=2, random_state = 0).fit(X)
kmeans.labels_
kmeans.predict([[0,0],[12,3]])
kmeans.cluster_centers_
