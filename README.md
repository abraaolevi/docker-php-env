How to use?

```
docker-compose up -d
```

# Docker for Building a Local Development Environment

This project provides a basic Docker setup, for building a local development environment for PHP application development.

## Why?

Why? Good question. But easy to answer. The intent is to provide a starting point for developers to get up and running quickly, using Docker, to build a local development environment. 

## Installation

To get up and running, after cloning the repository, either install Docker using your package manager of choice, if you’re running a Linux distribution. If you’re using either Mac OSX or Windows, download the respective Docker package installers: [Docker for Mac](https://docs.docker.com/docker-for-mac/) or [Docker for Windows](https://docs.docker.com/docker-for-windows/).

After that, add the cloned file and directory to the root of a PHP project. Then, run `docker-compose up -d`. This will boot Docker and build the containers for you.

## License

This project is licensed under the [MIT License](/LICENSE).