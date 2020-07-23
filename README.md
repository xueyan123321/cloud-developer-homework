# cloud-developer-homework

This is my udacity home assignment, and the whole content of the assignment is included in udacity-assignments directory.

## File structure

The udacity-frontend, udacity-restapi-feed and udacity-restapi-user directories include the docker files to build the docker images. 

Udacity deployment directory include docker directory and k8s directory:

In docker directory, we use `docker-compose-build.yaml` to rebuild all the docker images and `docker-compose.yaml` to create the corresponding container for the image to test locally.

In k8s directory, all the corresponding deployment files are here.
