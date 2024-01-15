# Witcher Book Series NLP Analysis


https://github.com/brian-w-zhang/witcher_project/assets/152770271/0dc9fb00-6737-446d-9a8e-d4dad1d59902


## Overview
This project delves into Natural Language Processing (NLP) techniques to perform an in-depth analysis of the Witcher book series, by Andrzej Sapkowski. The primary objectives include web scraping character names, employing Named Entity Recognition (NER), extracting intricate relationships, and conducting comprehensive network analysis.

### PyVis Graph with Community Detection
![image](https://github.com/brian-w-zhang/witcher_project/assets/152770271/7b62ba5f-8576-42ec-a24b-34ea47f2606d)

This image showcases a network graph generated using PyVis, visualizing the intricate relationships among characters in the Witcher book series. The community detection algorithm, specifically the Louvain algorithm, has been applied to uncover distinct character groups within the narrative. The colors represent different communities, providing insights into the social dynamics and connections between characters throughout the series. Additionally, the node sizes reflect the degree of each character, highlighting their importance in the network (Data from Sword of Destiny).

## Table of Contents
- [Technologies Used](#technologies-used)
- [Network Diagram Evolution](#network-diagram-evolution)
- [Centrality Graphs](#centrality-graphs)
- [Project Highlights](#project-highlights)
  - [Web Scraping & NER](#web-scraping--ner)
  - [Relationship Extraction & Network Analysis](#relationship-extraction--network-analysis)
  - [Temporal Analysis and Community Detection](#temporal-analysis-and-community-detection)
  - [Python Proficiency & Data Visualization](#python-proficiency--data-visualization)
- [Utilization of AI](#utilization-of-ai)
- [Project Impact](#project-impact)

## Technologies Used
- **Programming Language:** Python
- **Web Scraping:** Selenium
- **Data Manipulation:** pandas, numpy
- **Data Visualization:** Matplotlib
- **NLP:**
  - Named Entity Recognition (NER) using spaCy
  - Custom Relationship Extraction
- **Graph Analysis:** NetworkX
- **Community Detection Algorithm:** Louvain Algorithm

## Network Diagram Evolution

### Simple diagram generated using NetworkX
![image](https://github.com/brian-w-zhang/witcher_project/assets/152770271/77b07190-ae7a-4c8c-a64b-26a19591a0b7)

### First implementation of PyVis
![image](https://github.com/brian-w-zhang/witcher_project/assets/152770271/2a9c8ad3-655d-4fc3-8bfa-92b85a5e63e0)

### Increase node size based on degree
![image](https://github.com/brian-w-zhang/witcher_project/assets/152770271/e5ad42a5-ee81-4f44-95b5-d9b3bd9e3715)

### Add colours for community detection
![image](https://github.com/brian-w-zhang/witcher_project/assets/152770271/f5b23e3c-72bb-4a6f-b591-cd24febe4c5f)

## Centrality Graphs

### Degree Centrality
![image](https://github.com/brian-w-zhang/witcher_project/assets/152770271/f14914ca-bcb0-45df-8f1d-113c9216731a)
Degree centrality is a measure in network analysis that quantifies the importance of a node based on its connections. Specifically, it represents the number of direct connections or links a node has within a network. In simpler terms, nodes with higher degree centrality have more relationships or interactions with other nodes, signifying a greater influence or prominence in the network.

### Betweenness Centrality
![image](https://github.com/brian-w-zhang/witcher_project/assets/152770271/1fa601f7-4b5a-47fc-9dcc-d3aa978f87a9)
Betweenness centrality is a network analysis metric that identifies nodes that act as crucial intermediaries or bridges in a network. It measures the frequency with which a node lies on the shortest paths between other pairs of nodes. Nodes with higher betweenness centrality play a significant role in maintaining efficient communication within the network. They act as critical connectors, influencing the flow of information between different parts of the network. High betweenness centrality nodes are essential for maintaining network cohesion and facilitating communication between disparate groups of nodes.

### Closeness Centrality
![image](https://github.com/brian-w-zhang/witcher_project/assets/152770271/65f979b9-5290-496f-9d42-e1b259363ed5)
Closeness centrality is a network analysis metric that measures how quickly a node can reach other nodes in a network. It is calculated by determining the average length of the shortest paths between a node and all other nodes in the network. Nodes with higher closeness centrality are considered more central because they can efficiently communicate or transmit information to other nodes, acting as potential hubs for information flow within the network.

## Project Highlights

### Web Scraping & NER
- **What I Did:**
  - Extracted character names from the Witcher wiki using Selenium for efficient and structured data extraction.
  - Applied spaCy's NER for precise identification of character entities within the fantasy narrative.

### Relationship Extraction & Network Analysis
- **What I Did:**
  - Developed a custom relationship extraction model, leveraging co-occurrence of characters within a specified sentence window.
  - Utilized NetworkX for comprehensive graph analysis, creating a detailed social network graph of character connections.

### Temporal Analysis and Community Detection
- **What I Did:**
  - Conducted temporal analysis across multiple books, revealing the evolution of character importance throughout the series.
  - Employed the Louvain algorithm for community detection, uncovering distinct character groups within the narrative.

### Python Proficiency & Data Visualization
- **What I Did:**
  - Demonstrated expertise in Python programming for implementing advanced NLP techniques and graph analytics.
  - Utilized data visualization tools, including Matplotlib, to present complex relationships and character dynamics effectively.

## Utilization of AI
- **How AI was Used:**
  - Leveraged NLP techniques, including NER, for intelligent character identification.
  - Applied custom relationship extraction model to infer connections between characters.
  - Utilized Louvain algorithm for community detection, enabling the identification of character groups.

## Project Impact
The project provided a deep understanding of character relationships and their evolution throughout the Witcher book series. The use of NLP and graph analytics offered valuable insights into the dynamics of the narrative.

Feel free to explore the notebooks and adapt the code for your own analysis.
