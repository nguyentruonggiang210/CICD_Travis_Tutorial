[![Continous Integration and Deployment](https://github.com/nguyentruonggiang210/CICD_Travis_Tutorial/actions/workflows/github_pipeline.yaml/badge.svg)](https://github.com/nguyentruonggiang210/CICD_Travis_Tutorial/actions/workflows/github_pipeline.yaml.yaml)


[![CircleCI](https://dl.circleci.com/status-badge/img/gh/nguyentruonggiang210/CICD_Travis_Tutorial/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/nguyentruonggiang210/CICD_Travis_Tutorial/tree/main)

# Overview

This is a very simple, bare-bones NodeJS project created for you to use with Docker.

## Local Setup

**_Note_**: This is only needed if you want to run the app locally. You don't need to install the dependencies or run the server if you are running the code inside a Docker container.

- Install dependencies: `npm install`
- Run server: `node server.js`

## Container Setup

- Build image: `docker build .`
- Run container with image: `docker run {image_id}` where `image_id` can be retrieved by running `docker images` and found under the column `IMAGE ID`
- You can use the `-d` flag to run the container in the background. This will enable you to run other commands in your terminal while the container is running.

## Container Teardown

- Remove container: `docker kill {container_id}` where `container_id` can be retrieved by running `docker ps` and found under the column `CONTAINER ID`
