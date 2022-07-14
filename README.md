# Leveraging table semantics for dataset discovery

## Abstract

This project was developed as part of a thesis project at University of Amsterdam in the efforts to leverage column semantics for data discovery.

Automated semantic detection is a topic of interest to reduce time searching for datasets. However, many current implementations rely on using metadata to find a suitable dataset, making them prone to missing and inaccurate information that occurs in metadata.

Progress has been made in inferring the real-world concept, known as semantics, from values in a dataset. First, we coupled a semantic detector with a high-performance keyword-based search engine; then, we experimented with searching on a large dataset available from a well-known data retrieval competition. 

The goal is to understand how performance varies with column semantic enrichment. Using a public benchmark, we measure whether adding inferred semantic types for columns improves performance. Our experiments show that for this benchmark, there are limited to no improvements to the effectiveness of the search.

## Structure

This project consists of three key interactive notebooks organized by the tasks shown in the workflow below:
1. Task-1-sherlock-out-of-the-box (NTCIR dataset).ipynb
2. Task-2-prepare-merge-ingest-data.ipynb
3. Task-3-query-evaluate-performance.ipynb

## Workflow
![alt text](image/workflowv2.png?raw=true "Workflow for the experimental setup in leveraging column semantics for data discovery.")

