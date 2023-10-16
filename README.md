# QM matcher on docker
Run [the QM matcher](https://github.com/QuiltMC/qm-matcher) on a couple docker containers

## Prerequisites
You need the [Docker engine](https://docs.docker.com/engine/) with [Docker compose](https://docs.docker.com/compose/) installed. You also need git.

## Usage
1. Execute `./match [your old version] [your new version]` on a terminal (Git bash on Windows), and follow its instructions if required. As an example, to match `1.20.1` and `1.20.2`, you'd run `./match 1.20.1 1.20.2`
2. Once the script is finished, verify and push the changes to origin with your preferred tool
