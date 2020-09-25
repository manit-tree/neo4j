# neo4j

setup Neo4j container on your development machine

### instruction

1. to start container run "docker-compose up -d"
2. to shutdown container run "docker-compose down"

if everything is ok, Neo4J will run on port: 7474 and 7687
A volume is bound to ./data to allow the database to be persisted outside the container
By default, this requires you to login with neo4j/neo4j and change the password.
