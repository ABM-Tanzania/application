## Application
This repository only holds a docker-compose file which builds and runs a container of the automator and a container of the frontend. This means that by running the docker-compose file in this repository one can start the whole ABM-Tanzania application. Because the image of automator and the image of frontend are published on Docker Hub they don't have to be available locally. The docker-compose file accesses the images on Docker Hub.
## How to run
`docker-compose -f docker-compose.yml up --build` in terminal to run frontend and backend at the same time
- frontend will run on "localhost:3000"
- backend will run on "localhost:8080"