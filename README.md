# oss4geo-semantic

Data exploration scripts for oss4geo.org based on text embeddings for semantic search and topic clustering based on dimensionality reduction.

This is work in progress and needs some fine tuning but you can already explore the scatterplot based on text embeddings (bge-m3) and dimensionality reduction with tSNE. 

## To Do 
- improve script to access repos that are on GitHub but self-hosted GitLab instances or similar
- before creating the embeddings it might be best to let an LLM create a summary first. If there is too much code/special formatting etc. the embeddings might become inaccurate. They work best on clear textual descriptions of what the package does
- create a simple static frontend app (e.g. based on https://github.com/flekschas/regl-scatterplot/ or similar)
- create LLM-based labels of the clusters add the labels to the plot (e.g. one can see clusters for raster processing, CAD, stac and so on)

## Why? 
- We had a chat at https://earthmonitor.org/ 2024 and thought it might make for a good enhancement!
