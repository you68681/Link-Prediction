# Link-Prediction
#In this project, you will be learning from a training network and trying to predict whether edges exist among test node pairs.
#The training network is a partial crawl of the Twitter social network from several years ago. The nodes in the network—Twitter users—have been given randomly assigned IDs, and a directed edge from node A to B represents that user A follows B. The training network is a subgraph of the entire network. Starting from several random seed nodes, we proceeded to obtain the friends of the seeds, then their friends’ friends, and so on for several iterations.

#The test data is a list of 2,000 edges, and your task is to predict if each of those test edges are really edges in the Twitter network or are fake ones. 1,000 of these test edges are real and withheld from the training network, while the other 1,000 do not actually exist.

#All data will be available in raw text. The training graph data will given in a (tab delimited) edge list format, where each row represents a node and its out neighbours. For example:
#1 2
#2 3 
#4 3 5 1
