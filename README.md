# Social-Network-Analysis
Analysis of the social network made up of the councilors of the Madrid City Council and their interactions on Twitter
List of files:
- concejales.csv: Handmade list of usernames of all councilors and the party they belong to.
- twint_scrapping.ipynb: Notebook using Twint to get all tweets from councilors to other councilors.
- tweets_concejales.csv: This file is generated by twint_scrapping.ipynb and contains the tweets and the users who wrote them. It also has a lot of other information that is not used.
- creando_grafo.ipynb: From tweets_concejales.csv generates grafo_concejales.csv.
- grafo_concejales.csv: Contains the source, the target and the date of all the edges of the network.
- concejales.gephi: Gephi project created from grafo_concejales.csv.
- metricas.csv: Generated by councillors.gephi contains different network metrics.
- analisis.ipynb: Notebook in which the adjacency matrices are created and the graphs are drawn from concejales.csv, grafo_concejales.csv and metricas.csv.
- memoria.pdf: Project report where the data is analyzed and the process is explained.
