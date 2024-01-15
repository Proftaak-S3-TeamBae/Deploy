# TeamBae Deploy Files

These files are used to deploy the TeamBae project. TeamBae is an AI scanner, which is a compliance tool to detect and store which AI systems are being used in your IT environment.

## Prerequisites

Our deployment method requires using Docker. You can find more information about Docker [here](https://docs.docker.com/).

This project assumes Docker has been installed and working correctly.

## How to deploy

1. Clone this repository (and its submodules)
    - To ensure submodules are cloned, make sure to run `git clone git@github.com:Proftaak-S3-TeamBae/Deploy.git --recurse-submodules`.

2. Edit the example files. Some files will require you to rename them from `abc.example` to `abc`.

3. Run `docker compose up` to start all containers.