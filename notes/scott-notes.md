Elastic Search

Bullet point notes and questions
---------------------------------------

Facts:
  - Open Source
  - distributed search and analytics engine
  - based on Apache Lucene (What is that?)
  - is part of the elastic stack (What is that?)
  - Data is stored in JSON format
  - has full-text seach functionalities


## Glossary

### Index/indices
 An index is the largest unit of data in Elasticsearch and are comparable to databases when we think of relationsal databases.

 ### shards
 A shard is a single Lucene index. For a single index a shard is piece of the index. We can place each shards of a given index of different nodes so that you can more quickly search the index.

 ### documents
In relational database terminology this is analogous to a single row. There are no strict limits on how many documents can be stored on a single index.

### Clusters
These are a collection of one or more elastic search nodes. They have a unique identifier. In each cluster there is a single 'master' node.

### Replicas 
Copies of shards in the index used for backups and are not normally searched.




## Examples