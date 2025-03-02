# Installation
- Follow the Kafka quickstart: https://kafka.apache.org/quickstart
- Eg:
- Download kafka tar
- Extract tar
- Run:
```
$ bin/zookeeper-server-start.sh config/zookeeper.properties
$ bin/kafka-server-start.sh config/server.properties
```
- Once, create the topic 'security-baseline-events'
```
$ bin/kafka-topics.sh --create --topic security-baseline-events --bootstrap-server localhost:9092
````
- To view activity on the created topic (good for debugging), run:
```
bin/kafka-topics.sh --describe --topic security-baseline-events --bootstrap-server localhost:9092
```


