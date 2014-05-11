## Python Dockerfile


This repository contains **Dockerfile** of [Python](https://www.python.org/) for [Docker](https://www.docker.io/)'s [trusted build](https://index.docker.io/u/dockerfile/python/) published to the public [Docker Registry](https://index.docker.io/).


### Dependencies

* [dockerfile/ubuntu](http://dockerfile.github.io/#/ubuntu)


### Installation

1. Install [Docker](https://www.docker.io/).

2. Download [trusted build](https://index.docker.io/u/dockerfile/python/) from public [Docker Registry](https://index.docker.io/): `docker pull dockerfile/python`

   (alternatively, you can build an image from Dockerfile: `docker build -t="dockerfile/python" github.com/dockerfile/python`)


### Usage

    docker run -it --rm dockerfile/python

#### Run `python`

    docker run -it --rm dockerfile/python python
