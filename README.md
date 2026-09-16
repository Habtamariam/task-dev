# task-dev

Development infrastructure for hands-on practice.

`docker-compose.yml` starts local PostgreSQL and Redis containers. PostgreSQL
is exposed on `localhost:5433`, while Redis is exposed on `localhost:6380`.

Start the services with:

```bash
docker compose up -d
```

Stop the services with:

```bash
docker compose down
```
