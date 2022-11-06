# Nodejs Devops docker image

[Docker image link](https://hub.docker.com/r/zenbeni/nodejs_devops)

## Description

CI images with `docker in docker` as base (dind20, alpine 3.16), with `nodejs` installation for alpine (musl compatible installation), `yarn`, `Terraform`, `Terragrunt`, `AWS CLI V2` (compiled for Alpine linux), `Ansible`, `python3`.

This image enables easy nodejs CI jobs as `docker-compose` is for instance available, pushing to `AWS` is also possible with AWS CLI V2 and terraform/terragrunt.

## Versions

There are 3 images for every supported nodejs runtimes (only nodejs 14, 16 and 18 for now):
- nodejs_devops:14
- nodejs_devops:16
- nodejs_devops:18

## Docker image content

- Alpine Linux
- Docker In Docker
- Nodejs runtime
- Yarn
- Python3
- OpenSSH client
- Terraform
- Terragrunt
- Ansible
- AWS CLI V2
