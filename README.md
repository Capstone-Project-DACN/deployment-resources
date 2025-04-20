# Deployment-resources
This repo contains all the resources regarding to our Capstone Project (e.g. docker-compose file,....)

## Usage
```
docker compose -p <your-cluster-name> up -d
```

## Build your service's image
```
docker buildx build --platform=linux/amd64,linux/arm64 -t <your-dockerhub-username>/<your-service-name>:<tag> --push .
```
