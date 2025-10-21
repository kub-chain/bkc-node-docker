# KUB Chain - Lausanne Upgrade
Easy run KUB Chain Node


![Screenshot](images/screenshot-1.png "Grafana")

![Screenshot](images/screenshot-2.png "Stats")

### Running a Validator
```bash
# Run 
$ docker compose -f docker-compose.validator.yaml up -d
```


### Running a Fullnode
```bash
# Run 
$ docker compose -f docker-compose.fullnode.yaml up -d
```

### Running a Archivenode
```bash
# Run 
$ docker compose -f docker-compose.archivenode.yaml up -d
```

### Grafana Dashboard
- http://localhost:8080
```
username: admin
password: admin
```

### Stats Dashboard
- http://localhost:8090
