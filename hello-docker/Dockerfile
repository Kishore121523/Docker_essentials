# A Dockerfile is a script that contains instructions for building a Docker image. It defines the base image, sets up environment variables, installs software, and configures the container for a specific application or service.


# We have to run a javascript file hence we can use a node runtime from docker hub
# FROM - Specifies the base image for the Docker image.
FROM node:20-alpine

# We want to set the working directory to /app
# WORKDIR - Sets the working directory for subsequent instructions.
WORKDIR /app

# This will copy everything from the current directory to the docker image
# The first dot is the current directory on our machine and second directory is the path of the current directory within the container
# COPY - Copies files or directories from the build context to the container.
COPY . .

# Specify the command to run the app
# CMD executable(node) param1(hello.js)
CMD node hello.js

#Next we have to build an image from this dockerfile
# BUILD - Build an image from a Dockerfile:
# docker build -t image_name path_to_dockerfile - docker build -t hello-docker .



