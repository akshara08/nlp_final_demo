# nlp_final_demo
I analyzed the underlying tree structures of word2vec embeddings and compared it to wordnet trees to understand how much of hypernym/hyponym information they encode

# Word2Vec Trees
- Use the embeddings to find cosine distance between any 2 words
- These these distances as weigths between two nodes
- Construct a minimum spanning tree using Kruskal's algorithm

# Findings
- The precision, recall and f of edges predicted are not very impressive (0.29 for ~1000 trees)
- However, the degree centrality estimations are reliable (the mean difference ~0.08 for ~1000 trees)

# Meta
- The ipynb file should help you reproduce the results. You need to download Google's word2vec embeddings
