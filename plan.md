2 Dockerfiles:

1 for app
1 for postgres
<!-- 
go

alias CLD=docker rm -f $(docker ps -aq) && docker system prune -a 
. -->
docker build -t weightapp:1.0 .
docker run -d -p 2000:2000 weightapp:1.0

2. convert postgres into:
https://docs.docker.com/samples/postgresql_service/
Dockerfile
save the volume

docker run -d --name my-postgresdb-container -p 5432:5432 my-postgres-db

docker compose -

have both versions ready befor you proceed