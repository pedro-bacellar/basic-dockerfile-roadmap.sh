# Basic Dockerfile
## Description
A beginner project for roadmap.sh!

It will print "Hello, Captain!" to the console when you run the Docker image.

Everything was done in the terminal (readme and dockerfile).

## Prerequisites
- Git installed to clone the repository.
- Docker installed so you can run the image.

## Instructions
1. Clone repository
```bash
git clone https://github.com/pedro-bacellar/basic-dockerfile-roadmap.sh
cd basic-dockerfile-roadmap.sh
```

2. Build the Docker Image
```bash
docker build -t hello-captain .
```

3. Run the image
```bash
docker run hello-captain
```

4. Output
```bash
Hello, Captain!
```

## Roadmap.sh Requirements

The Dockerfile should be named Dockerfile.

The Dockerfile should be in the root directory of the project.

The base image should be alpine:latest.

The Dockerfile should contain a single instruction to print "Hello, Captain!" to the console before exiting.
