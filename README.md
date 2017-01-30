# google-gloud-sdk Docker image
[![Build Status](https://travis-ci.org/sbani/docker-google-gloud-sdk-alpine.svg?branch=master)](https://travis-ci.org/sbani/docker-google-gloud-sdk-alpine)

Slim Docker image for google cloud sdk based on alpine.

There are two Dockerfiles and tags inside this repo:

- Full version (`latest`, `full`)
- Slim version (`slim`)

All images are more or less the same like [google/cloud-sdk](https://hub.docker.com/r/google/cloud-sdk/) but smaller.

## Comparison:

Official image: ~1GB

Full: ~700MB

Slim: ~170MB

## Difference Full and Slim

*Slim* is without all the `--additional-components`. It's meant to have only the basic installation while *full* has all the additional components installed.
