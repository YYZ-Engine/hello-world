# YYZ-Engine Hello World 
[![Build Status](https://travis-ci.org/YYZ-Engine/hello-world.svg?branch=master)](https://travis-ci.org/YYZ-Engine/hello-world)
[![Coverage Status](https://coveralls.io/repos/github/yyz-engine/hello-world/badge.svg?branch=master)](https://coveralls.io/github/yyz-engine/hello-world?branch=master)

YYZ-Engine Hello World is a NodeJS Express React app for people to use and get a custom greeting based on local time and day, or get a country based on their location.

## Client-side Routes:
* [http://localhost:3000/hello](Hello) returns a custom greeting with an animation
* [http://localhost:3000/world](World) returns user's country

## API Routes: 
* [http://localhost:5000/api/hello](Hello) returns a greeting based on the local machine
* [http://localhost:5000/api/hello/monday](Hello/weekday) returns a greeting based on the local machine
* [http://localhost:5000/api/world](World) returns user's countryy

## Tools:
* NodeJS
* Express
* React
* Jasmine
* Jest

## To run this with npm:
To start up the application, complete the following steps:

1. Git clone the repository
2. npm install
3. cd client && npm install
4. cd ..
5. npm run dev

Check the available commands with `npm run` on package.json.

## To run this with Docker
To run the enviornment with [Docker](https://docs.docker.com/), install Docker, and then execute the following commands on the project root:

```
docker build --pull -t hello-world:latest .
docker run hello-world
```
