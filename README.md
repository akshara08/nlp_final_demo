# nlp_final_demo
I analyzed the underlying tree structures of word2vec embeddings and compared it to wordnet trees to understand how much conceptual information they encode

#Word2Vec Trees
- Use the embeddings to find cosine distance between any 2 words
- These these distances as weigths between two nodes
- Construct a minimum spanning tree using Kruskal's algorithm

#Findings:
-The precision, recall and f of edges predicted are not very impressive (0.29 for ~1000 trees)
-However, the degree centrality are pretty reliable (the mean error ~0.08 for ~1000 trees)
