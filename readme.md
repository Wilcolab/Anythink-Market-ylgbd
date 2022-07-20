# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Install Docker and Docker Compose

You can figure out how to do this in the official site: [docker official documentation](https://docs.docker.com/get-docker/).
Once you have followed the instructions, verify if docker is ready, using the command:

```sh
docker -v
```

and

```sh
docker-compose -v
```

### Run Docker Compose

Certify you are in the project root directory, then run the following command:

```sh
docker-compose up
```

### Test if all is up and running

For the backend:

Access this HTTP endpoint in your browser: [](http://localhost:3000/api/ping)

For the frontend:

Go to this route in your browser: [](http://localhost:3000/api/ping), and create your account!
