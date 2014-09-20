## Getting Started
### Installing Elastic Search(You know, for Search)

#### 1) Download && unzip latest distribution
[Download the latest version](http://www.elasticsearch.org/download/)

#### 2) Start Elasticsearch

```
$ bin/elasticsearch
```

#### 3) Run
```
$ curl 'http://localhost:9200'
```

### Installing Marvel(You know, for management)

#### 1) Install the Marvel plugin
```
./bin/plugin -i elasticsearch/marvel/latest
```

#### 2) Start Elasticsearch
```
$ bin/elasticsearch
```

#### 3) Use your browser to navigate
```
http://any-server-in-cluster:9200/_plugin/marvel/
```
