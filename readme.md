# IaC Computing - Lightsail

IaC computing component for lightsail instances.

This is atomic routine for any CI/CD such as gitlab-ci, bitbucket-pipelines etc.
In any case is possible to use it manually with run.sh helper script.

## Setup Development Environment

- Clone this repo: `git clone git@github.com:SindriaInc/iac-computing-lightsail.git`
- Move into it: `cd iac-computing-lightsail`
- Setup env: `cp .env.local .env`
- Setup docker compose: `cp docker-compose.local.yml docker-compose.yml`
- Start environment: `docker-compose up -d`