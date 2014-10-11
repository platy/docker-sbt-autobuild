#Docker SBT autobuild

## Builds docker container with:

- ubuntu 14.04
- openjdk7
- scala 2.11.0
- sbt 0.13.2


## Usage

All you should need for a basic build is a Dockerfile from this in the root of your sbt project. ie.

    FROM platy/sbt-autobuild:latest
    MAINTAINER Mike Bush <mpbush@gmail.com>


`docker compile` on your project will compile it

`docker run` will call `sbt run`

## Docker Hub
https://registry.hub.docker.com/u/platy/sbt-autobuild/
