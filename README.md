
## Overview

The project is simple and consists of three main services, each running in its own Docker container:

1. **Backend**: A Node.js application that serves the API and communicates with the MongoDB database.
2. **Frontend**: A Vue application that communicates with the backend via HTTP.
3. **MongoDB**: A NoSQL database used by the backend to store data.

## Docker Compose

Docker Compose is used to define and manage these services. The **docker-compose.yml** file sets up three containers and links them together in a network.

- The **Backend** container 
- The **Frontend** container 
- The **MongoDB** container

## Dockerfile of the backend and frontend
The dockerfiles and the images could be find in the folder of each of the service.

The docker compose file combines the two images and adds a third one for the MongoDB configuration.
