# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. First of all you need to clone this GitHub repository(clone it do not fork it).
2. You need to have ([docker](https://www.docker.com/)) and docker-compose both installed to make this project up and running.
3. To verify your installation use docker -v for docker and docker-compose -v for docker-compose.
4. Then run docker-compose up keep in mind that you need administrative privileges for running this command otherwise it will throw you error. This single command will make your frontend, backend and db up and running.
5. If docker is working correctly, the backend should be running and able to connect to your local database. you can test this by pointing your browser to http://localhost:3000/api/ping
6. If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
