# Deployment of V-SDGs

## Fetch submodules
```shell
git submodule init
git submodule update
```

## Configuration
```shell
cp BE/.env.example BE/.env
```

## Run docker
```shell
docker-compose --project-directory ./BE up -d
docker-compose --project-directory ./FE up -d
```