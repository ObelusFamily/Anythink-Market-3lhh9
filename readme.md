# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

To start the app user: `docker-compose up`
On the first time it might take a couple of minutes for the services to run (especially the frontend that need to install some stuff), so don't break your head, you just need to wait a few.
You can also see the docker logs in each machine console from the Docker UI.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.
