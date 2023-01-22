# README.md

Commands for docker-compose
Please, use this commands in this directory folder or maybe cannot works.

### Starting services
```
docker-compose -f "docker-compose.yml" up -d
```

### Stoping services
```
docker-compose down
```

### Stop with no volumes
```
docker-compose down --volumes
```

### Stop with no volumes and no images
```
docker-compose down --volumes --rmi
```