# Enhancing GNNs with Architecture-Agnostic Graph Transformations: A Systematic Analysis

This repository contains the source code for my master thesis project, **"Enhancing GNNs with Architecture-Agnostic Graph Transformations: A Systematic Analysis."** It also includes the implementation for the associated paper: [Enhancing GNNs with Architecture-Agnostic Graph Transformations: A Systematic Analysis
](https://arxiv.org/abs/2410.08759) and [Enhancing Molecular Property Prediction with GNNs via Architecture-Agnostic Graph Transformations](https://openreview.net/forum?id=Xp4vZ3eAwd&referrer=%5Bthe%20profile%20of%20Zhifei%20Li%5D(%2Fprofile%3Fid%3D~Zhifei_Li4))

## Overview

In recent years, a wide variety of graph neural networks (GNNs) have shown strengths across diverse tasks, yet challenges persist in achieving high expressivity and effective structural representation, especially for molecular data. Various techniques, including rewiring, lifting, and node annotation with centrality values, have been employed as pre-processing steps to enhance GNN performance. However, there are no universally accepted best practices, and the impact of architecture and pre-processing on performance often remains opaque.

This study systematically explores the impact of various isomorphism-preserving graph transformations as pre-processing steps on the performance of common GNN architectures using both synthetic datasets and real-world datasets. 
    

## Getting Started

### Prerequisites specified in `requirements.txt`

Install all required packages using:
```bash
pip install -r requirements.txt
