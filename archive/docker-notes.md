Docker Notes
============

* A Dockerfile can consist of a single line: `FROM ubuntu`
* To build the image from a `Dockerfile` in the current directory: `docker build .`
* To run an image: `docker run --rm -it ccc7a1`, where `ccc7a1` is any part of the hash for a given image (list the available images with `docker images`)
* Example: `docker run --rm -it python:3.6`
    * `--rm` means destroy when done
    * `-it` means interactive with terminal attached
    * We could do `-d` to run in background
* Some images available: `library/fedora`, `alpine` (small Linux)
* Sign up for a docker id on their website
* [Portainer](https://portainer.io) can be used to get a Web interface to your local Docker images
* Portainer instructs you to use the following command: `docker run -d -p 9000:9000 -v /var/run/docker.sock:/var/run/docker.sock portainer/portainer`
    * `-v` allows file in
* You can run the basic Docker Hello World with `docker --rm -it hello-world`
    * If you don't do the slash with `hello-world`, then it goes to the library online.
* To exit Docker container: exit
* `docker ps` (see what's running)
* `docker pull hello-world`  (no slash - library/, it's what Docker people themselves maintain)
* Adds `:latest` if you don't do a version number (meaning e.g. `:14.04` for Ubuntu Trusty)
* `docker ps -a` (see what you already ran)
* `docker images` (show images)
* `docker rmi 05a3` (remove image, can use any part of the hash)
* When we do run, it creates a container from the image.
* `docker logs`

Dockerfile: a script that lets you build an image or container or whatever.

`FROM ubuntu:14.04`

then: `docker build .`
or `docker build -f MyDockerfile .`

Dockerfile is executed every time you build the image.
