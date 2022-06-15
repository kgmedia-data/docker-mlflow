# docker-mlflow
Docker compose setup for MLFlow, Postgres and NGINX with basic authentication

## Export env
```bash
# mlflow backend database
export DB_NAME=mlflowdb
export DB_PORT=5432
export DB_USER=postgres
export DB_PW=

# aws credentials for store artifact
export AWS_ACCESS_KET_ID=
export AWS_SECRET_ACCESS_KEY=
export AWS_DEFAULT_REGION=
export ARTIFACTS= # s3://bucket-name/folder

# nginx auth
export AUTH_USER=
export AUTH_PASS=
```

## Run
```bash
docker-compose up -d --build
```