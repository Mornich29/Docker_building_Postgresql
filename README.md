# Docker-Postgresql-Sunday
 This is the repository for assesment.

## Docker and Postgres Setup:

1. Install Docker from https://www.docker.com/.
2. Pull the postgres-alpine by type "docker pull postgres:alpine"
3. Run the container by type "docker run --name name -e POSTGRES_PASSWORD=password -d -p 5432:5432 postgres:alpine". You can change password and name of the container.
4.type "docker exec -it name bash"
5.type "psql -U postgres"
6. Create Database by type "create database name_of_db"
7.create user role. You can add superuser role by type "CREATE ROLE name WITH LOGIN SUPERUSER PASSWORD 'password';"
8.connect to the Database by type "\c database name"

You can use fastapi with the database in Docker by follow the step from 
https://github.com/Mornich29/FastAPI-Postgresql-Sunday.git
