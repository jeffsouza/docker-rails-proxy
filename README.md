## Description

Set a proxy with Nginx for a Rails app running on port 3000

## What it includes?

- Nginx (latest)

## Before Run

Start a container with a Rails application listening on port 3000

## Run

```bash
$ docker container run -p 80:80 --link NAME_RAILS_APP_CONTAINER:app IMAGE_NAME
```
