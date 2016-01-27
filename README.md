## Docker-Ubuntu

This repository contains **Dockerfile** of [Ubuntu](http://www.ubuntu.com/) with a few additional packages for [Docker](https://www.docker.com/)'s [automated build](https://hub.docker.com/r/fdabrandao/docker-ubuntu/) published to the public [Docker Hub Registry](https://hub.docker.com/).

* GiHub repository: <https://github.com/fdabrandao/docker-ubuntu>
* BitBucket repository: <https://bitbucket.org/fdabrandao/docker-ubuntu>
* Docker repository: <https://hub.docker.com/r/fdabrandao/docker-ubuntu/>


### Base Docker Image

* [ubuntu:trusty](https://registry.hub.docker.com/u/library/ubuntu/)


### Additional packages

* `g++-4.8`
* `automake`
* `python2.7`
* `python3.5`
* `python-pip`
* `python3-pip`
* `python-virtualenv`
* `glpk-utils`
* `libglpk-dev`


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://hub.docker.com/r/fdabrandao/docker-ubuntu/) from public [Docker Hub Registry](https://hub.docker.com/):

   `docker pull fdabrandao/docker-ubuntu`

   (alternatively, you can build an image from Dockerfile:

   `docker build -t fdabrandao/docker-ubuntu github.com/fdabrandao/docker-ubuntu`)


### Usage

    docker run -it --rm fdabrandao/docker-ubuntu
