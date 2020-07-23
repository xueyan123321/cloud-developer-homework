# cloud-developer-homework

This is my udacity home assignment, and the whole content of the assignment is included in udacity-assignments directory.

## File structure

The udacity-frontend, udacity-restapi-feed and udacity-restapi-user directories include the docker files to build the docker images. 

Udacity deployment directory include docker directory and k8s directory:

In docker directory, we use `docker-compose-build.yaml` to rebuild all the docker images and `docker-compose.yaml` to create the corresponding container for the image to test locally.

In k8s directory, all the corresponding deployment files are here.

## CI/CD

Actually, I have been successful in putting Docker image into DockerHub, but I don't know how to deal with kubeconfig. I have looked up lots of information involving this problem and can't solve this problem. I have no clue about how to deploy to AWS EKS. Hope to get some clues from my mentor.

![travis results](https://github.com/xueyan123321/cloud-developer-homework/blob/06-ci/newImage/ciAndCdsuccess.png?raw=true)

## DOCKER Image

This is my dockerHub image

![Docker images](https://github.com/xueyan123321/cloud-developer-homework/blob/06-ci/newImage/docker-hub-image.png?raw=true)

## Deploy in EKS

![deploy in EKS](https://github.com/xueyan123321/cloud-developer-homework/blob/06-ci/newImage/apps%20is%20deployed%20in%20kubeclusterinfo.png?raw=true)

## Deploy without Downtime

![deploy without downtime](https://github.com/xueyan123321/cloud-developer-homework/blob/06-ci/newImage/updatingWithout%20Downtime.png?raw=true)

## A/B deployment

![a/b deployment](https://github.com/xueyan123321/cloud-developer-homework/blob/06-ci/newImage/two_version_serve_content.png?raw=true)