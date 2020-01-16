# Heterogeneous-Deep-Graph-Infomax

Parameter Setting:

#HDGI-A: <br>
Node-level dimension: 16<br>
Attention head: 4<br>
Semantic-level attention vector: 8<br>
learning rate: 0.02<br>
Drop out ratio: 0.6<br>

#HDGI-C: 
Node-level dimension: 64
Semantic-level attention vector: 8
learning rate: 0.02
Drop out ratio: 0.6

#GAT:
Node-level dimension: 16
Attention head: 4
learning rate: 0.005
Drop out ratio: 0.6

#GCN:
Hidden-unit dimension: 64
learning rate: 0.01
Drop out ratio: 0.5

#RGCN:
Hidden-unit dimension: 16
learning rate: 0.01
Drop out ratio: 0

#Metapath2Vec:
Embedding dimension: 100
learning rate: 0.01
negative-samples: 5
Window: 1

#HAN:
Node-level dimension: 16
Attention head: 4
Semantic-level dimension: 8
learning rate: 0.005
Node-level Drop out ratio: 0.6
Semantic-level Drop out ratio: 0.6

#Deepwalk:
Number of walks per node: 10
Dimensions of word embeddings: 128
Length of random walk: 30
Window size for skipgram: 5

#DGI:
Hidden-unit dimension: 64
learning rate: 0.001
Drop out ratio: 0

