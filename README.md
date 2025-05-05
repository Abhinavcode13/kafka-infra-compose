A Docker Compose setup for a Kafka cluster with 3 `brokers` and 3 Zookeeper nodes.

## Quick Start

```bash
# Copy environment file
cp env.example .env

# Start the cluster
docker-compose up -d

# Check status
docker-compose ps
```

## Access Points

- Zookeeper: `localhost:2181`, `localhost:2182`, `localhost:2183`
- Kafka: `localhost:29092`, `localhost:29093`, `localhost:29094`

## Cleanup

```bash
# Stop cluster
docker-compose down

# Remove volumes
docker-compose down -v
``` 