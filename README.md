# hello-efk
> Logging solution: EFK(Elasticsearch + Fluentd + Kibana)

# Quickstart
- build fluentd image
```shell
docker build -t fluentd-elasticsearch ./fluentd
```
- run services
```shell
docker-compose up -d
```
