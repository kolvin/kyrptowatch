# Krytpowatch
![Alt text](.docs/service-ui.png?raw=true "Optional Title")

# Local Environment Visual
![Alt text](.docs/dev-env-visual.png?raw=true "Optional Title")


# Prerequisites
- [Docker](https://docs.docker.com/get-docker/) + [Docker Compose](https://docs.docker.com/compose/install/) are required to run the project

# Starting the project

```
cp .env.example .env
docker-compose up -d
```

`Then vist; ` **_http://0.0.0.0:3000_**`


# Execute Service Commands
```
docker-compose exec <service> <command>

ie: docker-compose exec app npm ...
ie: docker-compose exec app npx ...
```

# Testing

```
docker-compose exec app npm test
```