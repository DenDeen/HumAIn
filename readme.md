# Neo4j + Grafana API

## Installation 
1. Pull from Github
2. Insert variables in docker-compose file (e.g. port, password and username)
3. CLI cd to root directory
4. docker-compose up (make sure docker is installed)
5. flask should be able to connect to your neo4j database
6. Open grafana and install the infinity datasource
7. Query the neo4j database by querying the flask API with the infinity datasource


## Default Credentials
- NEO4J_HOST=host.docker.internal
- NEO4J_PORT=7687
- NEO4J_USERNAME=neo4j
- NEO4J_PASSWORD=abiss
- NEO4J_DATABASE_NAME=powerplant
