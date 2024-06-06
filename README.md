# Kafka and Redpanda for local development

### Description
Rapid deployment of local environment **Apache Kafka** and **Redpanda Console (UI)** for development 

### Quick Start
 
```shell
docker run -d --network host --name redpanda-console -e KAFKA_BROKERS=localhost:9092 docker.redpanda.com/redpandadata/console:latest
```
