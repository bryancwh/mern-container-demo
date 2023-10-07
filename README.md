# mern-container-demo

This repository contains files that deploys a dockerized MERN-stack web application. There are 4 components:
1. server - this folder contains code to build the back-end Node.js application using the Express.js framework. This will help us process all transactions and communication that we need to make to the MySQL database. In this case, we will use a CRUD to implement a simple Node.js Rest API.
2. client - this folder contains code to build the front-end application using React. The front-end logic will process all the API endpoints that we have defined in the back-end.
3. nginx - this folder contains code to build the Nginx instance. In this application, we will access both the client and the server using the Nginx proxy  
4. docker-compose.yml - docker compose is used to string together the 3 seperate containerized components above.