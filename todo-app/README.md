# Todo app

University of Helsinki — DevOps with Kubernetes, Exercise 1.2.

## Description

A minimal HTTP server that prints its listening port at startup.

The port can be configured with the PORT environment variable.
The default port is 8080.

## Build

Run from the repository root:

    docker build -t todo-app:1.2 ./todo-app

## Run locally

    docker run --rm -e PORT=8081 -p 8081:8081 todo-app:1.2

Test the HTTP endpoint at http://localhost:8081.
