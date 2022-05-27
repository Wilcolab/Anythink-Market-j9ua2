# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install Docker on your local machine
1. Clone this repo to your local machine
1. Run Docker and test the connection to the database by heading to [http://localhost:3000/api/ping](http://localhost:3000/api/ping)
> Note, make sure to start docker. If you receive an error ensure Docker is running on your machine. 
1. Check that the frontend is connected by heading to [http://localhost:3001/register](http://localhost:3001/register)
1. Register a new user with the form on screen. 
