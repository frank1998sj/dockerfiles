Apache Kafka docker compose file for development.

## How to use

### Start the container stack

```bash
HOST_IP=<host_ip_in_local_network> docker-compose -f docker-compose.yaml up -d
```

Web UI will appear on [localhost:8080](http://localhost:8080) if no port clash occurs.

You may find [kcat](https://github.com/edenhill/kcat) quite useful.

