# Code

### In this directory, there are 3 main coding notebooks for each of the 3 graph algorithms we have implemented. These algorithms utilize the inherent graph nature of BART lines to solve logistical problems involved in our proposed BART-Truck hybrid system for food delivery.

## Weighted_shortest_paths.ipynb
This weighted shortest paths algorithm will allow us to determine the best route for inventory to take from the BART stop closest to the AGM distribution center (call it BART stop A) to the designated BART stop for customers to directly pick-up or for trucker's to pick-up for truck-delivery (call it BART stop B).

## Betweenness_centrality.ipynb
Betweenness centrality involves calculating how often a node lies on the shortest path between other pairs of nodes. We will construct our graph such that there is only one node ber BART station. Our connections will represent directions of lines and transfers, and they will be weighted by travel time. Nodes with high betweenness will have a high impact if they are shut down or have delays.

## Degree_centrality.ipynb
Degree centrality involves counting the number of direct connections a node has. This algorithm helps us find BART stations that are overloaded with connections and likely to be busy and crowded. The graph will be constructed such that there is only one node for every BART station. The relationships between nodes represent connetions betweens stations in both directions for each line. The relationships are weighted by travel time.
