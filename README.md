# Build an Analytics API using FastAPI + Time-series Postgres

Own your data pipeline! 

Start by building an Analytics API service with Python, FastAPI, and Time-series Postgres with TimescaleDB


## Uvicorn

- `uvicorn main:app --reload` or `uvicorn main:app --host 127.0.0.1 --port 8000 --reload`

## Docker

- `docker build -t py_analytics_api:v1 -f Dockerfile.web .`
- `docker run py_analytics_api:v1`

and for development it becomes

- `docker-compose up --build`
- `docker-compose up --watch`
- `docker-compose down` or `docker-compose down -v` (to remove volumes)
- `docker-compose run app /bin/bash` or `docker-compose run app python` 