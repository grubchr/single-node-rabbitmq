# single-node-rabbitmq

Single node RabbitMQ docker container.

## Create a .env file

```bash
RABBITMQ_DEFAULT_USER=admin
RABBITMQ_DEFAULT_PASS=password
```

## Deploy

```bash
docker-compose up -d
```

Explicitly specify the .env file

```bash
docker-compose --env-file .env up -d
```

## Shutdown

```bash
docker-compose down
```
