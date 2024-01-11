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

docker-compose run --rm app npm install <package name> e.g TypeORM or DrizzleORM
`![Screenshot 2024-01-05 124038](https://github.com/nidumolu/nest-docker-postgresdb/assets/13748087/10140fa2-3689-4861-93e3-67aad5c0c70f)

![Screenshot 2024-01-05 124118](https://github.com/nidumolu/nest-docker-postgresdb/assets/13748087/5d9f1c90-ac85-4bdf-a1ed-8b6d9318ac06)

``

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can connect to pgAdmin by visiting http://localhost:5050 in our web browser

Added swagger functionality as well to test apis that will get added
![Screenshot 2024-01-11 134150](https://github.com/nidumolu/nest-docker-postgresdb/assets/13748087/1b366bd8-1d14-48d6-b54b-c026d67b3e86)

