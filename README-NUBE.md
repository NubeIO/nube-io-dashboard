# README

## How to Build Locally

```bash
make build-go
make build-js
```

## How to Run Locally

```bash
./bin/darwin-amd64/grafana-server
```

## How to Build Docker Image

```bash
docker build -t rubix-dashboard .
docker tag rubix-dashboard:latest nubeio/rubix-dashboard:<VERSION>
```

## How to Run Locally

```bash
docker run -d --name=rubix-dashboard -p 3001:3000 rubix-dashboard
```

## How to push in DockerHub

```bash
docker login
docker image push nubeio/rubix-dashboard:<VERSION>
```

## Current version

```
VERSION=1.0.0
```
