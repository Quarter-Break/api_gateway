# API Gateway
.NET Core 5.0 API gateway with Ocelot.

## Getting Started
```zsh
dotnet build
```
```zsh
dotnet restore
```
```zsh
dotnet run
```

## Run with Docker
```
docker-compose up --build
```

#### Error: Docker Network Missing
If you get the following error:
Network `qbreak-network` declared as external, but could not be found. Run the following:
```zsh
docker network create qbreak-network
```
<i>Note: a Docker network is required to allow the container to communicate with other containers.</i>

#### Resources

Ocelot: https://codewithmukesh.com/blog/microservice-architecture-in-aspnet-core/
