# KUB Chain - Test Network


### Clone
```bash
$ git clone https://github.com/kub-chain/bkc-node-docker.git
$ cd bkc-node-docker/testnet
```

### Setup
Create the secrets directory before running any node for the first time. This directory is required by the entrypoint script to store the keystore password and account files.

```bash
$ mkdir -p secret/keystore
```

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
