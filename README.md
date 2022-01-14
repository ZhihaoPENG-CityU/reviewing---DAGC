# DAGC
MM21_EXTENSION


## Q&A
* Q1: What we use the cosine similarity measure as a distance measure to construct graph data for non-graph datasets?
* A1: The previous methods listed two approaches of constructing the KNN graph, whereas the details with respect to each non-graph dataset are not clear.
* A2: KNN graph construction with the Euclidean distance measure fails to exploit the geometric structure information and hence cannot provide an effective KNN graph. Instead, we use the cosine similarity measure as a distance measure to conduct the KNN-k graph construction, since two samples owing to the same cluster tend to have larger absolute cosine values than those lying in different clusters.
