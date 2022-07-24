# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Download and Install [Docker](https://docs.docker.com/get-docker/)
2. Verify docker is installed properly by entering the following commands into terminal `docker -v` & `docker-compose -v`
3. If a version for both is shown, run `docker-compose up` in terminal to build the project.
4. verify backend is up by pointing to [http://localhost:3000/api/ping](http://localhost:3000/api/ping) in your browser
5. verify frontend is up by pointing to [http://localhost:3001/register](http://localhost:3001/register) in your browser
6. if you haven't already, register for an account on the front end to use locally.
