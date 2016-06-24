[![Docker Stars](https://img.shields.io/docker/stars/jessewei/tensorflow-watson.svg?style=flat-square)](https://hub.docker.com/r/jessewei/tensorflow-watson/)
[![Docker Pulls](https://img.shields.io/docker/pulls/jessewei/tensorflow-watson.svg?style=flat-square)](https://hub.docker.com/r/jessewei/tensorflow-watson/)

# Using TensorFlow and Watson

This directory contains `Dockerfile`s to make it easy to get up and running with
TensorFlow via [Docker](http://www.docker.com/).

Those utilites included for [IBM Watson service](https://console.ng.bluemix.net/) laboratory are listed as below:
- Google Cloud API
- Watson SDK for nodejs and python
- Node.js: json-query

## Installing Docker

General installation instructions are
[on the Docker site](https://docs.docker.com/installation/), but we give some
quick links here:

* [OSX](https://docs.docker.com/installation/mac/): [docker toolbox](https://www.docker.com/toolbox)
* [ubuntu](https://docs.docker.com/installation/ubuntulinux/)

## Which containers exist?

Base images: `gcr.io/tensorflow/tensorflow` - TensorFlow with all dependencies - CPU only!
[Docker Hub](https://hub.docker.com/r/tensorflow/tensorflow/tags/).


## Running the container

Run non-GPU container using

    $ docker run -it -p 8888:8888 jessewei/tensorflow-watson

` 
### Notebook list
The notebook naming start from api and kernel used.