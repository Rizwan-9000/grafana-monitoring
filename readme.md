## Make sure you have prerequisite tools
[Docker](https://www.docker.com/)
[Docker-Compose](https://docs.docker.com/compose/)

## Before running the Compose file make sure you have necessary Docker Volumes
## You can check the Volumes by this command:
```bash
docker volume ls
```

## You can Create the Volume by this command:
```bash
docker volume create grafana-data
```

## To Run the Docker Compose file use this command:
```bash
docker-compose -f monitoring.yaml up -d
```
