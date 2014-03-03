sirona-collector-cassandra
==========================

Apache Sirona Collector configured to store data in Apache Cassandra

Just run:
```
mvn tomcat7:run
```

Send data to: http://localhost:9090/sirona-collector/collector

Have a look at sirona.properties file to see Cassandra configuration

```
org.apache.sirona.cube.CubeBuilder.collector = http://localhost:9090/sirona-collector/collector
``
