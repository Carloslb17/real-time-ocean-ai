
# Real time data Processing

## Public avaible real time data sources

https://github.com/bytewax/awesome-public-real-time-datasets


1 - Handling Dockers
- Documentation docker compose.
https://docs.docker.com/compose/gettingstarted/

- Introduction guide.
https://docs.docker.com/get-started/workshop/02_our_app/


- Create image of postgres
'''shell
docker pull postgres  

docker run --name data-engineering-postgres -e POSTGRES_PASSWORD=secret -d postgres

docker exec -u postgres data-engineering-postgres createdb postgres-db  

docker exec -it data-engineering-postgres psql -U postgres -d postgres-db
'''  
- Kafka documentation
