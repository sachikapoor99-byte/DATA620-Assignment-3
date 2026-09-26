# DATA 620 Assignment 3: Graph Visualization

## Facebook Social Network Analysis

This project analyzes the Facebook Social Circles dataset from the Stanford Network Analysis Project (SNAP). Each node represents an anonymized Facebook user, and each edge represents a friendship between two users.

## Dataset

- Source: [Stanford SNAP Facebook Social Circles](https://snap.stanford.edu/data/ego-Facebook.html)
- Network type: Undirected
- Nodes: 4,039
- Edges: 88,234

## Analysis

The project uses Python and NetworkX to calculate:

- Graph diameter
- Network density
- Average clustering coefficient
- Average degree
- Degree centrality
- Most connected users

## Key Results

- Diameter: 8
- Network density: 0.0108
- Average clustering coefficient: 0.6055
- Average degree: 43.69
- Most connected user: Node 107 with 1,045 connections

## Visualizations

The project includes:

- A bar chart comparing the five most connected users
- A network visualization centered on the most connected user

A 150-node subset was used for the network visualization because displaying all 4,039 nodes and 88,234 edges would be difficult to interpret.

## Repository Files

- `DATA620_Assignment3_Sachi_Kapoor.ipynb`: Complete analysis and explanations
- `facebook_combined.txt.gz`: SNAP Facebook edge-list dataset
- `facebook_network_visualization.png`: Network visualization
- `top_five_connected_users.png`: Degree comparison bar chart

## Tools

- Python
- NetworkX
- pandas
- Matplotlib

## Video Presentation

Video link: [Watch the video presentation](https://youtu.be/tMD6239tvcw)
