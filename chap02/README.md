```zsh
docker run --rm --name prom  -d -p 9090:9090 prom/prometheus
docker ps
docker stop prom
```

```zsh
docker-compose up -d
docker-compose ps
docker-compose down -v
```