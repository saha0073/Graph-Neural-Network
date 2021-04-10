# Graph-Neural-Network

## Skills employed

* Modelling Techniques: Graph-based Neural Network Models - Graph Convolutional Network
* Tech Stack: Python, Jupyter
* Libraries: Numpy, Pandas, Skimage, Sklearn, Matplotlib, Tensorflow (Keras)
* Statistical Techniques: Principal Component Analysis, k-Means

## Graph Neural Network (GNN)

Graph Neural Network is a type of Neural Network which directly operates on the Graph structure. A typical application of GNN is node classification. Essentially, every node in the graph is associated with a label, and each node has a set of features defining it. In the case of social network graphs, this could be age, gender, country of residence, political leaning, and so on. Each edge may connect nodes together that have similar features. And we want to predict the label of the nodes without ground-truth.

## Graph Convolution Network (GCN)
There are quite a few types of GNN, such as Graph Convolution Network, Graph LSTM, Gated GNN and among them GCNs are most popular & most widely used GNN. 'Convolution' operation in GCN is very similar to the Convolution in CNN architecture. GCN very powerful neural network architecture for machine learning on graphs. In fact, they are so powerful that even a randomly initiated 2-layer GCN can produce useful feature representations of nodes in networks. The figure below illustrates a 2-dimensional representation of each node in a network produced by such a GCN. 

## References
* A Gentle Introduction to Graph Neural Networks (Basics, DeepWalk, and GraphSage) by Kung-Hsiang Huang in [Medium](https://towardsdatascience.com/a-gentle-introduction-to-graph-neural-network-basics-deepwalk-and-graphsage-db5d540d50b3).

* How to do Deep Learning on Graphs with Graph Convolutional Networks by Tobias Skovgaard Jepsen in [Medium](https://towardsdatascience.com/how-to-do-deep-learning-on-graphs-with-graph-convolutional-networks-7d2250723780). 

* Kipf, Thomas N., and Max Welling. "Semi-supervised classification with graph convolutional networks." arXiv preprint arXiv:1609.02907 (2016).
