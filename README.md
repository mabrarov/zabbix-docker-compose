# Docker Compose project for local Zabbix

## Requirements

1. Docker 20+
1. [Docker Compose](https://docs.docker.com/compose/):
    * [Docker Compose standalone](https://docs.docker.com/compose/install/standalone/) 2+ or
    * [Docker Compose plugin](https://docs.docker.com/compose/install/linux/) (this README commands use Docker Compose plugin syntax)

## Running

```bash
docker compose up -d
```

## Accessing

| Link | Username | Password |
|---|---|---|
| http://localhost/ | Admin | zabbix |

## Stopping

```bash
docker compose stop
```

## Removing

```bash
docker compose down -v -t 0
```
