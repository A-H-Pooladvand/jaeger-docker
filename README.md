# Jaeger Docker
Docker-compose configuration for quick deployment of jaeger


## Prerequisites

* Docker installed and running (https://docs.docker.com/engine/install/)
* Docker Compose installed and running (https://docs.docker.com/compose/install/)

## Usage
1. **Start the services:**

   ```bash
   docker-compose up -d
   ```
This will create and start both the postgres and pgadmin containers in detached mode (background).

2. **Access Jaeger UI:**

   - Open your web browser and navigate to `http://localhost:16686`.

## Stopping and Removing Services
- Stop:

```Bash
docker-compose stop
```
- Remove:

```Bash
docker-compose down
```
