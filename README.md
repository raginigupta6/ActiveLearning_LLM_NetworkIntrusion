# Addressing Concept Drift in Network Intrusion Detection Systems

## Overview

This repository explores various strategies for addressing concept drift in Network Intrusion Detection Systems (NIDS). Concept drift refers to the phenomenon where the statistical properties of the target variable change over time, adversely affecting the performance of machine learning models. This project investigates several techniques to mitigate the impact of concept drift, including:

- **Query By Committee (QBC)**
- **Active Domain Adaptation via Clustering Uncertainty-weighted Embeddings (CLUE)**
- **Uncertainty Sampling**
- **CoreSet-based Sample Selection**

Additionally, we leverage Large Language Models (LLMs) to augment minority class data, specifically focusing on enhancing datasets related to botnet, DoS, and DDoS attacks.

## Dataset

This project utilizes datasets from the [CIC Dataset](https://www.unb.ca/cic/datasets/ids-2018.html, https://www.unb.ca/cic/datasets/ids-2017.html), which provides a variety of network traffic datasets for intrusion detection research in two different timelines. You can download the datasets directly from their website.

## Objectives

- Implement strategies for detecting and mitigating concept drift in NIDS.
- Evaluate the effectiveness of these strategies in improving model performance.
- Use LLMs to generate synthetic data for underrepresented attack classes.

## Features

- **Concept Drift Detection**: Tools and methods for identifying concept drift in NIDS.
- **Data Augmentation**: Techniques to augment datasets for minority classes using LLMs.
- **Model Evaluation**: Framework for assessing the performance of various strategies on NIDS tasks.
