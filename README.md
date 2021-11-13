# docker node and redis app

## Project live link: https://github.com/HabibulHH/noderedisdocker

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

This system powered by

- Javascript
- Node js
- Express js
- npm
- redis

## Features

- Can show visit count

## Installation

- Download the project from github repo link
- cd noderedisdocker
- run docker-compose up
- Visit web on localhost 4001

## some useful docker command

```sh
docker run -d redis
docker build .
docker build -t hirahasan44/web:latest .
docker stop $(docker ps -a -q) to stop all containers
docker rm $(docker ps -a -q) to remove all memory
docker-compose down
```

## Starting the server in prod mode
