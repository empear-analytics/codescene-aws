# codescene-aws

This repository contains configurations for running Codescene on AWS.
Note that all configurations use self-signed certificates generated during instance creation.

## Create a CloudFormation stack running CodeScene behind nginx using docker

Use [codescene-onprem-nginx-docker.template](codescene-onprem-nginx-docker.template) to create a CloudFormation stack with a single EC2 instance running CodeScene behind nginx using docker.

## Create a CloudFormation stack running Codescene behind nginx

Use [codescene-onprem-nginx.template](codescene-onprem-nginx.template) to create a CloudFormation stack with a single EC2 instance running CodeScene behind nginx.

## Start CodeScene behind nginx using docker-compose

Use [docker.compose.yml](docker.compose.yml) for starting CodeScene behind nginx on an existing EC2 instance.