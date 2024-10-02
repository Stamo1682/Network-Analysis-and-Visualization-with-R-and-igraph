This project performs a network analysis and visualization of character interactions in George R.R. Martin’s “A Song of Ice and Fire” series. Using the igraph package in R, an undirected weighted graph is created to examine the relationships between characters based on interaction data from a .csv file (asoiaf-all-edges.csv).

Key tasks include:

Constructing a weighted graph from character interaction data.
Exploring basic network properties, including number of vertices, edges, diameter, clustering coefficients, and identifying important characters based on degree and weighted degree.
Plotting the entire network and a subgraph for characters with at least 9 connections.
Analyzing centrality measures (closeness, betweenness, and PageRank).
Ranking characters based on PageRank and adjusting visualizations accordingly.

Outputs
* Graph Visualizations: Two plots of the network are generated—one for the entire network and another for the subgraph with characters having more than 9 connections.
* Centrality Measures: Tables listing the top 15 characters according to closeness and betweenness centrality.
* PageRank: A ranked list of characters based on their PageRank value, with a visualization where node sizes reflect PageRank importance.

References
* Beveridge, A., & Shan, J. (2016). Network of Thrones. Math Horizons Magazine, 23(4), 18-22.
* igraph R package documentation: https://igraph.org/r/
