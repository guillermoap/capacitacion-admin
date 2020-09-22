# December Labs - PIS 2020

# Setup
## Define `$PARENT_PWD` env var

This can be hardcoded with the root dev folder.

UNIX users can add this to .bash_profile

    export PARENT_PWD="$(dirname "$(pwd)")"

## Copy `.env.example` and rename to `.env`

Add corresponding config values

## Copy `docker-compose.example.yml` and rename to `docker-compose.yml`

# Running
To run the project simply run

    docker-compose up

This will spin up the `admin` instance.
To spin up the instance with a new build add the `--build` flag as so

    docker-compose up --build

Go to `http://localhost:5001/` and you should see the project up and running
