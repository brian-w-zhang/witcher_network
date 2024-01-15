# Witcher Book Series NLP Analysis

## Overview
This project delves into Natural Language Processing (NLP) techniques to perform an in-depth analysis of the Witcher book series. The primary objectives include web scraping character names, employing Named Entity Recognition (NER), extracting intricate relationships, and conducting comprehensive network analysis.

### PyVis Graph with Community Detection
![image](https://github.com/brian-w-zhang/witcher_project/assets/152770271/7b62ba5f-8576-42ec-a24b-34ea47f2606d)

This image showcases a network graph generated using PyVis, visualizing the intricate relationships among characters in the Witcher book series. The community detection algorithm, specifically the Louvain algorithm, has been applied to uncover distinct character groups within the narrative. The colors represent different communities, providing insights into the social dynamics and connections between characters throughout the series. Additionally, the node sizes reflect the degree of each character, highlighting their importance in the network.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Network Diagram Evolution](#network-diagram-evolution)
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



![image](https://github.com/brian-w-zhang/witcher_project/assets/152770271/2a9c8ad3-655d-4fc3-8bfa-92b85a5e63e0)

First implementation of PyVis

![image](https://github.com/brian-w-zhang/witcher_project/assets/152770271/e5ad42a5-ee81-4f44-95b5-d9b3bd9e3715)

Increase node size based on degree

![image](https://github.com/brian-w-zhang/witcher_project/assets/152770271/f5b23e3c-72bb-4a6f-b591-cd24febe4c5f)

Add colours for community detection

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
