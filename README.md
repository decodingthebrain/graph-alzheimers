![Brain Graph](long-range-brain-graph-transformer-1.png)

# Graph Neural Network for Cognitive Score Prediction with EEG
Predicting MMSE and MOCA scores using functional connectivity (FC) to build brain graphs as input for Graph Neural Networks (GNN). 

## Introduction
Most researcher paper's that incorporate Alzheimer's & EEG-based data for the purposes of deep learning employ classification tasks. This project aims to focus on a regression task - predicting cognitive scores - using brain graphs as the input for GNNs. Graphs are a type of data that have 3 building blocks: nodes (vertices), edges (relationships), and properties (features) and are useful when depecting data that have a relationship such as friends in a social network, molecular bonds between elements, and road network for Google maps. As mentioned properties can be captured within nodes and/or edges to provide rich information about the data. 
EEG data has a natural graph-like structure where electrodes act as nodes, and we can form edges between nodes based different functional connectivity measures. This effectively creates a unqiue graph based on the brain coupling. This study aims to find the best brain graph structure for predicting cognitive scores of diagnosed patients.
