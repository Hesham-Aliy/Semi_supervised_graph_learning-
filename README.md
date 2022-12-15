Semi-supervised learning is a machine learning method that falls between supervised and unsupervised learning. In Supervised learning, a model is trained on a labeled dataset, where the correct output is provided for each example in the training set. In Unsupervised learning, the model is not provided with labeled training examples, and must find patterns and relationships in the data on its own.

In semi-supervised learning, the model is trained on a dataset that is partially labeled. This means that only some of the examples in the training set have known, correct outputs. The model is then able to use this information, along with the patterns it finds in the unlabeled data, to make predictions on new examples.



<div id="header" align="center">
  <img src="images/Semi_supervised.png" />
</div>


while the inductive way is focused on predicting all


# What Are Graph Neural Network?

Graph neural network is one of the most Deep learning hot topics nowadays that has many applications in real world; as the graphs are everywhere around us. Many types of data will be better is it represented in a graph data structure as graphs are not taking huge memory size as complex architectures as Convolution Neural Networks https://arxiv.org/abs/1901.00596. 

In this Repo we reimplemented some of graph neural networks that working in a transductive way (Semi supervised). 

# 1- Graph Attention Networks

graph attention networks (GATs), novel neural network architectures that operate on graph-structured data, leveraging masked self-attentional layers to address the shortcomings of prior methods based on graph convolutions or their approximations. By stacking layers in which nodes are able to attend over their neighborhoods' features, we enable (implicitly) specifying different weights to different nodes in a neighborhood, without requiring any kind of costly matrix operation (such as inversion) or depending on knowing the graph structure upfront.



<div id="header" align="center">
  <img src="images/GAT_schematic.PNG" />
</div>


# 2- Graph convlutional Netowrks



<div id="header" align="center">
  <img src="images/figure.png" />
</div>

