# DevOps-pipeline
Repository for DevOps with docker course's 3.1 to build pipeline.

Content copied from courses material: https://github.com/docker-hy/material-applications

## Run

docker build -t reverseproxy ./nginx
docker-compose up

## About Pipeline to Heroku
I decided to only push the frontend to Heroku.

Pipeline implemented in ./github/workflows/build.yml

API ke has been regenerated so it can not be used anymore.
