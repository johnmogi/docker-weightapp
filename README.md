# docker-weightapp

1. brung the weightapp to local dev using 2 containers.

2. next- an additional docker compose and we're good for k8s.

plating with the weightapp locally then azure cloudly and maybe awssy (:

# docker-weightapp


status: works but no db connection
in order to build the connection it needs to figure out the pghost.
which is dynamic - it resolves after the setup...

steps to reproduce:
docker inspect <container_db> | grep IPAddress
then this value can be inserted into the app .env

