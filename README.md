# Nodejs Devops docker image

## Description

CI images with docker in docker as base (dind20, alpine 3.16), with nodejs installation for alpine (musl compatible installation), yarn, Terraform, Terragrunt, AWS CLI V2, Ansible, python3.

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
