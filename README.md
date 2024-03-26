
# Angular Template Project

This project is meant to be a blank template for starting docker based development of Angular front ends.

## What you need first
- Probably want the latest NodeJS and NPM installed
- Docker needs to be installed
- Depending on your rig, you may need docker compose (but a real os has it included ;)

## Pertinent commands

- if you need to install angular cli sudo npm install - g @angular/cli
- ng new app - create a new app
- cd template then ng serve --open to serve without docker

## Docker
So, this will allow you to modify the project and your changes will be automatically updated in the browser. Unless you change it, the server should be running on http://localhost:4200.

To build the docker image: docker compose build
To run the image: docker compose up

