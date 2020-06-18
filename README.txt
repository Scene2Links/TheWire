TheWire_S01.mat is a MAT file containing the adjacency matrix for Season 1 of the HBO TV series. The file contains several variables related to properties of the network.

Aij - Adjacency matrix (undirected network where edge strength represents shared screen time between two nodes)
Aij_multi - Multilayer adjacency matrix where each slice represents a minute of data. Any characters that appear in the same scene are considered connected (all episodes concatenated)
edgeList - Undirected edge list: Column 1 = Source, Column 2 = Target, Column 3 = Weight
edgeName - Edge list with character names: Column 1 = Source, Column 2 = Target, Column 3 = Weight
N - Number of nodes
nodeActor - Actor label for node
nodeList - Numeric ID associated with node
nodeName - Character label for node
screenTime - Amount of screen time for individual character (in minutes)
timeGraph - Node-time chart with each row representing a character, and column representing when a character appears (all episodes concatenated)
