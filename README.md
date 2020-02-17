# Docker Compose ELK stack setup
Simple to run Docker Compose setup for everyone who wants to get familiar with basics of ELK stack

## How to run

### Requisites

- Docker Engine (the latest tested version: 19.03)
- Docker Compose (the latest tested version: 1.24.1)

### Run

1. Open CLI
2. Go to the project folder
3. Run the following command:
> docker-compose -f docker-compose.yml up -d
4. Check service availability
- Kibana: http://localhost:5601
- Elasticsearch HTTP: http://localhost:9200
