# docker-insy
Docker container setup files for InSy

## Setup
A running traefik container using the network `traefik` is required.
1. Clone the repository
2. Copy the example .env file and adjust the values as needed.   
```
  cp .env.example .env
  nano .env
```
3. Start the docker container
```
  docker compose up -d
```
