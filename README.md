# 1. Register MYSQL Source connector
```bash
curl -i -X POST -H "Accept:application/json" -H "Content-Type:application/json" http://localhost:8083/connectors/ -d @source.json
```

# 2. Register PostgreSQL sink
```bash
curl -i -X POST -H "Accept:application/json" -H "Content-Type:application/json" http://localhost:8083/connectors/ -d @jdbc-sink.json
```# debezium-mysql
