# Log output

A minimal application for the University of Helsinki
DevOps with Kubernetes course.

## Behavior

- Generates a UUID when the application starts.
- Prints the same UUID every five seconds.
- Prefixes every log entry with a UTC timestamp.

## Build

Run from the repository root:

    docker build -t log-output:1.1 ./log-output

## Run locally

    docker run --rm log-output:1.1
