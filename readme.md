# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

## Steps for Setup

1. Install Docker on your Machine
1. Check you installation on the terminal with following commands:
	- `docker -v` 
	- `docker-compose -v`
1. Then go inside the project Directory and run `docker-compose up` to load frontend and backend of the project
1. You may check the if the backend is up and running by opening[TestCheck](http://localhost:3000/api/ping)on your browser 
1. Also go ahead and check if the [frontendCheck](http://localhost:3001/register)
### Finally your Setup is Completed!
