# How to run reviews service

## License

 MIT License

## Prerequisite



 JAVA

```
/opt/ibm/wlp/bin/server run defaultServer
```

# How to run with Docker

```bash
# Build Docker Image for reviews service
docker build -t reviews .

# Run details service on port 8082 .
docker run -d --name reviews -p 8082:9080 -e ENABLE_RATINGS=true reviews

```

## How to run with Docker Compose

```bash
docker-compose up
```