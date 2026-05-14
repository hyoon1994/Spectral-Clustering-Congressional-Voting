# Spectral Clustering of Congressional Voting Networks

Spectral clustering and semi-supervised learning applied to U.S. congressional voting data using graph Laplacians.

## Overview

This project analyzes the voting behavior of members of the 1984 U.S. House of Representatives using spectral clustering and graph-based machine learning methods.

Each congress member is represented by a voting vector across 16 bills, and pairwise similarities are used to construct a weighted voting network. The graph Laplacian is then used to uncover the underlying political structure of the network.

The project demonstrates how graph-based learning methods can recover political party structure directly from voting behavior without using party labels.

---

## Research Goals

The main goals of this project are to:

- construct a similarity graph from congressional voting records
- apply spectral clustering using the graph Laplacian
- analyze the effect of the Gaussian similarity parameter
- classify political parties using the Fiedler vector
- implement semi-supervised learning using Laplacian embeddings

---

## Methods

This project was implemented in Python using:

- NumPy
- SciPy
- Matplotlib
- spectral clustering
- graph Laplacians
- semi-supervised regression

Key methods include:

- Gaussian similarity graphs
- Laplacian matrix construction
- eigenvalue decomposition
- Fiedler vector clustering
- Laplacian embeddings
- least-squares semi-supervised learning

---

## Results

The spectral clustering model successfully recovered the underlying political party structure from voting behavior alone.

Key findings include:

- spectral clustering achieved approximately 88% classification accuracy
- the optimal Gaussian similarity parameter was approximately σ = 2.1
- semi-supervised learning achieved up to 92.9% accuracy using Laplacian embeddings
- graph-based features effectively captured the structure of the congressional voting network

---

## Project Significance

This project demonstrates how graph-based machine learning methods can uncover political and institutional structure from relational data.

The results show that spectral methods are effective for analyzing voting networks and can achieve strong classification performance even with limited labeled data.

Hyo Jung Yoon  
University of Washington  
Applied & Computational Mathematics
