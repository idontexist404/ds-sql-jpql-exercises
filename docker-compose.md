09/05/2024

# Docker compose instructions (PostgreSQL + PgAdmin)
https://www.danieldcs.com/postgresql-e-pgadmin-com-docker-compose/

It is important to create a docker network: `docker network create local-network`

## Solving pgadimin writing permission:
https://stackoverflow.com/questions/64781245/permission-denied-var-lib-pgadmin-sessions-in-docker

`sudo chown -R 5050:5050 ${DATA_PATH_HOST}/pgadmin`