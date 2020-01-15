You must start a kafka server to make this run from kafka\bin\windows
 ```
kafka-server-start.bat ..\..\config\server.properties
kafka-topics.bat --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic kafka-test
```