# docker-compose-local
Docker compose files for local testing


ELK stack
```
docker-compose-elk.yml

Start
docker-compose -f docker-compose-elk.yml up -d

Check status of docker-compose cluster
docker-compose ps -a

Cluster Node Info
curl http://localhost:9200/_nodes?pretty=true

Access Kibana
http://localhost:5601

Access Elasticsearch
http://localhost:9200

Check cluster health
curl http://localhost:9200/_cluster/health?pretty

Access ElasticHQ
http://localhost:5000




````

