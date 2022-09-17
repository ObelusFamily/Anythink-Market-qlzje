# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
1. git pull the repo
2. Install docker and verify it by running the following commands in the terminal: docker-v and docker-compose -v
3. Run docker-compose up from the porject root directory to load Anything's backend and frontend.
4. Test if the backend is running by running the following url in browser: http://localhost:3000/api/ping
5. Test if frontend is connected to backend by pointing browser to: http://localhost:3001/register 
