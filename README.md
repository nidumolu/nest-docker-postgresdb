This is a [Nest.js](https://nestjs.com/) project bootstrapped with [`nest new <your project name>`].


## Getting Started

check if you have docker and docker compose setup / installed on your machine

```bash
docker -v
docker-compose -v
```

Building the docker image
```bash
docker build -t docker-nest .
```

## How to run the application

Run the development server:

```bash
docker-compose up
```
To install new dependencies

```bash
docker-compose run --rm app npm install <package name> e.g TypeORM or DrizzleORM
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can connect to pgAdmin by visiting http://localhost:5050 in our web browser
