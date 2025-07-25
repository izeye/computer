# Elasticsearch
## Elasticsearch Reference
### Getting Started
* Installation
  * https://www.elastic.co/guide/en/elasticsearch/reference/current/_installation.html

### Set up Elasticsearch
#### Important System Configuration
* Virtual memory
  * https://www.elastic.co/guide/en/elasticsearch/reference/current/vm-max-map-count.html

#### Bootstrap Checks
* System call filter check
  * https://www.elastic.co/guide/en/elasticsearch/reference/master/_system_call_filter_check.html

#### Set up X-Pack
* Set up X-Pack
  * https://www.elastic.co/guide/en/elasticsearch/reference/5.5/setup-xpack.html
* Installing X-Pack in Elasticsearch
  * https://www.elastic.co/guide/en/elasticsearch/reference/5.5/installing-xpack-es.html

### Search APIs
#### Request Body Search
* Scroll
  * https://www.elastic.co/guide/en/elasticsearch/reference/2.3/search-request-scroll.html

### Mapping
* Mapping
  * https://www.elastic.co/guide/en/elasticsearch/reference/current/mapping.html

#### Metadata fields
* [`_source` field](https://www.elastic.co/guide/en/elasticsearch/reference/current/mapping-source-field.html)

#### Mapping parameters
* doc_values
  * https://www.elastic.co/guide/en/elasticsearch/reference/current/doc-values.html
* fielddata
  * https://www.elastic.co/guide/en/elasticsearch/reference/current/fielddata.html

### Modules
* Network Settings
  * https://www.elastic.co/guide/en/elasticsearch/reference/current/modules-network.html

### Index Modules
#### Merge
* Merge
  * https://www.elastic.co/guide/en/elasticsearch/reference/current/index-modules-merge.html

#### Store
* Store
  * https://www.elastic.co/guide/en/elasticsearch/reference/current/index-modules-store.html
* Pre-loading data into the file system cache
  * https://www.elastic.co/guide/en/elasticsearch/reference/current/_pre_loading_data_into_the_file_system_cache.html

### [Index templates](https://www.elastic.co/guide/en/elasticsearch/reference/current/index-templates.html)

## Elasticsearch: The Definitive Guide
### Getting Started
#### Inside a Shard
* Segment Merging
  * https://www.elastic.co/guide/en/elasticsearch/guide/current/merge-process.html

### Search in Depth
#### Structured Search
* Dealing with Null Values
  * https://www.elastic.co/guide/en/elasticsearch/guide/current/_dealing_with_null_values.html

### Administration, Monitoring, and Deployment
#### Production Deployment
* Don’t Touch These Settings!
  * https://www.elastic.co/guide/en/elasticsearch/guide/current/_don_8217_t_touch_these_settings.html

#### Post-Deployment
* Indexing Performance Tips
  * https://www.elastic.co/guide/en/elasticsearch/guide/current/indexing-performance.html

## Java API
### Maven Repository
* Maven Repository
  * https://www.elastic.co/guide/en/elasticsearch/client/java-api/current/_maven_repository.html

### Client
* Client
  * https://www.elastic.co/guide/en/elasticsearch/client/java-api/current/client.html
* Transport Client
  * https://www.elastic.co/guide/en/elasticsearch/client/java-api/current/transport-client.html

### Search API
* Using scrolls in Java
  * https://www.elastic.co/guide/en/elasticsearch/client/java-api/current/java-search-scrolling.html

## Kibana User Guide
### Introduction
* Introduction
  * https://www.elastic.co/guide/en/kibana/current/introduction.html

### Set Up Kibana
* Set Up Kibana
  * https://www.elastic.co/guide/en/kibana/current/setup.html
* Installing Kibana
  * https://www.elastic.co/guide/en/kibana/current/install.html
* Install Kibana with .tar.gz
  * https://www.elastic.co/guide/en/kibana/current/targz.html

### Set Up X-Pack
* Set Up X-Pack
  * https://www.elastic.co/guide/en/kibana/5.5/setup-xpack-kb.html
* Installing X-Pack in Kibana
  * https://www.elastic.co/guide/en/kibana/5.5/installing-xpack-kb.html

## X-Pack for the Elastic Stack
### Introduction
* Introduction
  * https://www.elastic.co/guide/en/x-pack/current/xpack-introduction.html
* Installing X-Pack
  * https://www.elastic.co/guide/en/x-pack/current/installing-xpack.html

## Java REST Client
### Java Low Level REST Client
* [Sniffer](https://www.elastic.co/guide/en/elasticsearch/client/java-rest/current/sniffer.html)
  * [Usage](https://www.elastic.co/guide/en/elasticsearch/client/java-rest/current/_usage.html)

### Java High Level REST Client
* Getting started
  * [Compatibility](https://www.elastic.co/guide/en/elasticsearch/client/java-rest/current/java-rest-high-compatibility.html)

## Elasticsearch Java API Client
### [Introduction](https://www.elastic.co/guide/en/elasticsearch/client/java-api-client/current/introduction.html)
### Getting started
* [Installation](https://www.elastic.co/guide/en/elasticsearch/client/java-api-client/current/installation.html)
* [Connecting](https://www.elastic.co/guide/en/elasticsearch/client/java-api-client/current/connecting.html)

### [Using the Java API Client](https://www.elastic.co/guide/en/elasticsearch/client/java-api-client/current/usage.html)
* [Indexing single document](https://www.elastic.co/guide/en/elasticsearch/client/java-api-client/current/indexing.html)

## Blogs
* [A Heap of Trouble](https://www.elastic.co/blog/a-heap-of-trouble)
* [Clustering Across Multiple Data Centers](https://www.elastic.co/blog/clustering_across_multiple_data_centers)
* [Disk-Based Field Data a.k.a. Doc Values](https://www.elastic.co/blog/disk-based-field-data-a-k-a-doc-values)
* [Elasticsearch tips: inserting vs. updating your index](https://blog.codecentric.de/en/2014/12/elasticsearch-usage-tipps-transform-update-heavy-index-heavy-indexing/)
* [How to resolve unassigned shards in Elasticsearch](https://www.datadoghq.com/blog/elasticsearch-unassigned-shards/)
* [Lucene's Handling of Deleted Documents](https://www.elastic.co/blog/lucenes-handling-of-deleted-documents)
* [OpenSearch vs. Elasticsearch: Which is Better?](https://www.chaossearch.io/blog/opensearch-vs-elasticsearch-comparison)
* [Support in the Wild: My Biggest Elasticsearch Problem at Scale](https://www.elastic.co/blog/support-in-the-wild-my-biggest-elasticsearch-problem-at-scale)
