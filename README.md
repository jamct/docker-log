# Docker Logging with Kibana and Fluentd

Demo project on collecting docker logs. Using Kibana, Fluentd and Elasticsearch.

## Getting started

Just run `docker-compose up`. After a few minutes Kibana will respond at "localhost:5601". To create some logs, just open "localhost:80" a few times.

This project is not ready for production use! Make sure to add some kind of authorization in front of your Kibana Dashboards.

## Documentation

The usage is described in German c't magazine (08/2020). [Container-Logbücher](https://www.heise.de/select/ct/2020/8/2000809334796828694)