# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Environment 

Docker makes it easier to run things locally
 verify docker is ready by running **docker -v**  then **docker-compose -v** in the terminal
  terminal will show successful message when done
  then run **docker-compose up** to load backend and frontend 
  point to http://localhost:3000/api/ping in browser to get backend up and running
  port 3001 is register which is the front end
   use **docker-compose up** or **docker exec** to run commands on a running container