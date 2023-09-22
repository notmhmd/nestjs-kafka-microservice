# **getting started**

- install docker
- install docker-compose
- clone the repo
- initializing the app

**installing docker**

you can follow the steps [here](https://docs.docker.com/install/).
they should be pretty simple :)

**installing docker-compose**

follow the steps [here](https://docs.docker.com/compose/install/)

**clone the repo**

    git clone --recurse-submodules https://github.com/notmhmd/nestjs-kafka-microservice

**initializing the app**

cd into the file until you find `docker-compose.yml` and then just type the following

    docker compose build & docker compose up -d

that's it :)

notes:
if you want to know where to send your requests you can

    docker inspect api_gateway_ [dev - prod] | grep IP

p.s. store the IP in environment variables for ease

