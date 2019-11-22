# Stms-Elk-Win
 ELK for Windows
 
 Run the latest version of the [Elastic stack][elk-stack] with Docker and Docker Compose.

It gives you the ability to analyze any data set by using the searching/aggregation capabilities of Elasticsearch and
the visualization power of Kibana.

Based on the official Docker images from Elastic:

* [elasticsearch](https://github.com/elastic/elasticsearch-docker)
* [logstash](https://github.com/elastic/logstash-docker)
* [kibana](https://github.com/elastic/kibana-docker)

## Requirements

### Host setup

* Install: "Docker for Windows Installer.exe"
* Install: git
* 16 GB of RAM (At leaset)

By default, the stack exposes the following ports:
* 9200: Nginx load balancing port
* 9300: Elasticsearch TCP transport
* 5601: Kibana

## Installtion

Open CMD as Administrator:

```console
git clone https://github.com/Netlims/Stms-Elk-Win.git
cd Stms-Elk-Win/
docker-compose up
```



