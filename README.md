# Chart for Curator

Elasticsearch Curator helps you curate, or manage, your Elasticsearch indices by:
* Obtaining the full list of indices from the cluster, as the *actionable list*
* Iterating through a list of user-defined [filters](https://www.elastic.co/guide/en/elasticsearch/client/curator/current/filters.html) to progressively remove indices from the *actionable* list as needed.

Our Chart deletes all logstash-prefixed indices older than 14 days.

[Curator github](https://github.com/elastic/curator)    
[Curator Reference Documentation](https://www.elastic.co/guide/en/elasticsearch/client/curator/current/index.html)            
[Discuss Curator](https://discuss.elastic.co/search?q=curator)
