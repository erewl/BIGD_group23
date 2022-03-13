# Big Data Project - Group 23


## Setup

Installing python dependencies in a virtual environment

```bash
# Creation of the virtual environment
python -m venv ./bigd

# Installation of dependencies
pip install -r requirements.txt
```
And then you can mount this environment with: 
```bash
# when using fish
source ./bigd/bin/activate.fish
# or other (multiple activation scripts are in this folder)
source ./bigd/bin/activate
```

To start the spark cluster, use [docker-compose](https://docs.docker.com/compose/install/) (in Mac this comes out of the box with Docker Desktop, for others refer to the [Install Instructions](https://docs.docker.com/compose/install/))

```bash
# to start all containers
docker-compose up 

# or to just start a dedicated container by name
docker-compose up spark
```
---
## Spark Overview
https://surfdrive.surf.nl/files/index.php/s/0gfxnfn1jnngoi6