# Kafka Cluster Topologies
Contains several reference designs of Kafka clusters with inter- and 
intra-cluster replication &amp; high availability settings

```
# set Docker host IP
export DOCKER_HOST_IP="<your docker host IP>"

# bring up containers via Docker compose
docker-compose -f .\ZK-single_KAFKA-ha_CONNECT-ha.yml up
```
