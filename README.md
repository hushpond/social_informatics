# Social_informatics
# Musician-Network-Analysis
### Subgroup Community Detection and Centrality Analysis of the Korean Music Industry

This repository implements a comprehensive network analysis of collaborative relationships among Korean musicians. By utilizing the Louvain Algorithm for community detection and various centrality metrics, this project identifies key influencers and structural subgroups within different musical genres including R&B, Rock, Ballad, and Dance.

---

## System Overview
The project analyzes the structural topology of the Korean music industry's collaboration network. It aims to identify how musicians are clustered into sub-communities and which individuals act as "hubs" or "bridges" within and across genres. The analysis provides a quantitative look at the industry's collaborative dynamics beyond simple popularity metrics.

---

## Technical Specifications

### Core Algorithms and Metrics
* Community Detection: Louvain Algorithm for modularity-based subgroup discovery.
* Centrality Metrics: Degree Centrality, Betweenness Centrality, and Eigenvector Centrality.
* Visualization: Graph-based layout representing nodes (musicians) and edges (collaborations).

### Standardized Centrality Indicators
* Degree Centrality: Identifies the most frequently collaborating musicians.
* Betweenness Centrality: Identifies "bridge" musicians who connect different subgroups.
* Eigenvector Centrality: Measures the influence of a musician based on the influence of their collaborators.

---

## Methodology

### 1. Louvain Community Detection
* Implemented the Louvain algorithm to partition the global collaboration network into high-modularity subgroups.
* Successfully identified distinct communities that align with genre-specific production teams and labels.

### 2. Genre-Specific Subgroup Analysis
The network was filtered and analyzed across four major domains to identify dominant players:

* R&B: Identified key nodes such as BIG Naughty (서동현), Kristin Carpenter, and WOOGIE. BIG Naughty showed the highest Betweenness Centrality (0.5), acting as a primary bridge in the genre.
* Rock/Metal: Analyzed the DAY6-centered network and IU’s collaborative cluster. DAY6 and Young K showed maximum Degree and Eigenvector Centrality (1.0).
* Ballad: Evaluated clusters around MSG Wannabe (M.O.M), IU, and prolific producers like Kim Do-hoon (RBW) and Park Geun-tae.
* Dance/Idol: Analyzed large-scale girl group networks including BLACKPINK, IVE, and LE SSERAFIM, distinguishing between "highly connected" mainstream clusters and "isolated" specialized production teams (e.g., ADOR/NewJeans or The Black Label).

---

## Key Results and Evaluation

### Quantitative Centrality Rankings
* Degree Centrality Hubs: Young K (DAY6), Kristin Carpenter, and MSG Wannabe achieved top scores (1.0) in their respective genres.
* Betweenness Centrality (Bridges): Musicians like BIG Naughty (0.5 in R&B) and IU (1.0 in Ballad/Rock) were identified as critical nodes that link otherwise disparate clusters.
* Eigenvector Centrality (Influencers): High scores for producers like Hong Ji-sang and Kim Do-hoon highlight the influence of key composers in forming industry-wide collaboration patterns.

### Qualitative Structural Insights
* Identified "Isolated" vs. "Connected" clusters within the Dance/Idol genre. For instance, the analysis showed how certain groups (e.g., NewJeans via Minji/Hanni) maintain highly specialized, isolated networks compared to the more interconnected mainstream idol groups.
* Demonstrated that collaboration in the Korean music industry is heavily driven by producer-artist relationships, with certain producers acting as the central anchors for entire sub-communities.

---

<img width="1572" height="882" alt="image" src="https://github.com/user-attachments/assets/8dcae339-9248-4960-bac0-a8051a82642c" />

<img width="1555" height="862" alt="image" src="https://github.com/user-attachments/assets/dcd1334f-eba4-4779-892b-f4bda0e8c4d5" />

<img width="1575" height="876" alt="image" src="https://github.com/user-attachments/assets/42df6b14-3d7c-414d-a3ca-88c5dd2059bd" />

<img width="890" height="657" alt="image" src="https://github.com/user-attachments/assets/d416ed3b-d710-4b4c-8322-87cc477b914d" />



