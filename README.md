# Analysis of Complex Networks

## Homework 1

### Instructions

1. Please make sure you download the Group 9 data
2. Make sure you have the homework_1.ipynb file in the same directory as the folders Facebook-Ego and Twitter-Ego
3. Please run all the cells in homework_1.ipynb in order
4. In case the .ipynb file is corrupted you can find an update version in the repository https://github.com/othmane-mahfoud/hw_1_complex_networks/tree/main

### Assumptions

1. The Description.txt files mention "The 'ego' node does not appear, but it is assumed that they follow every node id that appears in this file.". Therefore for both Facebook and Twitter, whenever there is an edge between node 1 and node 2, I also add an edge from ego to node 1 and to node 2.
2. Since it was not specified, I did not separate between in and out-degrees for Twitter's directed graph when calculating the maximum and average degree of the network.