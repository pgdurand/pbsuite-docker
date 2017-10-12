# pbsuite-docker

A Dockerized version of PBSuite software.

## Installation

There is no installation procedure. However, you will have to have Docker installed on your system.

Run a 'git clone' of this project on your computer, then read the next section.

## Build the Docker image

Simply type:

    docker build -t pbsuite-15.8.24 -f Dockerfile-pbsuite-15.8.24 .

## Test the container

Simply type:

    docker run -it --rm pbsuite-15.8.24
    cd /tmp
    Jelly setup protocol.xml
    Jelly mapping protocol.xml

## Issues

See issue 1.

