# python-web-api-bottle-basic-auth-ssl-postgres-pop

## Description
Creates an api of `pop` for a bottle project.
Has the ability to query by parameters.

Remotely tested with *testify*, the ssl is not verified.

Requires basic authentication for endpoints.

| username | password |
| -------- | -------- |
| *user* | *pass* |

## Tech stack
- python
  - bottle
  - sqlalchemy
  - testify
  - requests
- postgres

## Docker stack
- python:latest
- postgresql:alpine

## To run
`sudo ./install.sh -u`
- Get all pops: https://localhost/pop
  - Schema id, name, and color

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
