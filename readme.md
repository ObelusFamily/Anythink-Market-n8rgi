# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Setup

- Install and run Docker. Follow the [Get Docker | Docker Documentation](https://docs.docker.com/get-docker/)

### Run

- Run `docker-compose up` from the project root directory to load Anythink's backend and frontend
- Ping http://localhost:3000/api/ping to confirm the backend is running
- Create a fresh test user following the http://localhost:3001/register path to confirm the communication between the frontend and the backend
