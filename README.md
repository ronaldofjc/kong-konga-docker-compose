# Kong and Konga - API Gateway

Use the latest version of kong and konga, and do not need to compile, directly pull the official image to run.

Four containers:

- kong-database : postgres
- kong-migrations : kong
- kong : kong
- konga : konga


### Pre-Requires

- Docker 


## Install

- Command: 

`docker-compose up -d`


## Usage Kong

`http://localhost:8001`


## Usage Konga

`http://localhost:1337`
