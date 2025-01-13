---
marp: true
theme: thg-accelerator
footer: "![](../thg-accelerator-theme/accelerator-logo.svg)"
style: |
  img[alt~="centre"] {
    display: block;
    margin: 0 auto;
  }
---

# Elasticsearch

Scott Stirling & Hernán Ibarra

# What is Elasticsearch

- It is a horizontally distrubuted NoSQL (non-relational) database/ search engine.
- To make search and update the database elastic search (Behaves like/uses a RESTful API) using HTTP request - GET, POST, PUT, DELETE etc to make queries.
- Designed for very fast searching and analytics.

# What is OpenSearch

# How Does it work

- Relational database
- Inverse index (because querying faster)
- Shards (to horizontally scale faster)
- Nodes (More computating)
- Cluster
- Indexes (templates for different types of data, address within the cluster)

# Cap Theorem Details

# Licensing

- It was open source until around 2021.
- It is now no longer open source (some details to follow).

# Who uses it and why?

- Uber uses it for it searching and storing geo-spatial data.
- Netflix uses Elastic Search for its recommendation system.
