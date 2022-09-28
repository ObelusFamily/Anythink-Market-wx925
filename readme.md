# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

1. Before you want to run the code you need to install docker first. Just go to docker offical website and install it.

2. After completing installation of docker you can run 
docker -v and docker-compose -v to check is docker work properly.

3. Then run docker-compose up from the project root directory to load project backend and frontend.

4. Then copy paste  http://localhost:3000/api/ping in your browser to check all works fine.

5. At this http://localhost:3001/register you will create a new user and check all backend and database works fine.

6. That's all you are good to go.