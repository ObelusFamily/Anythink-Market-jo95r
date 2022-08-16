# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

First make sure docker is installed and running.

1. In the terminal go to the folder where the "docker-compose.yml" file is located and execute the below line.

``docker-compose up``

(It will take a file to install all dependencies and setup)

2. After It is setup you can check if it is running by going to the url: http://localhost:3000/api/ping