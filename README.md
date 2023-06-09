# CIFAR-10 Classifier (Building and Running Docker Image)

To build the docker image from the dockerfile
-----------------------------------------

sudo docker build -t classifier .

To list the docker images
------------------

sudo docker images

To run the docker image
-----------------------

sudo docker run -d -p 8080:8000 --name cifar classifier

To list the running docker containers
-------------------------------------

sudo docker ps

To stop the running docker container
------------------------------------

sudo docker stop cifar

To start the docker container again
-----------------------------------

sudo docker start cifar

To restart the docker container
-------------------------------

sudo docker restart cifar

To remove the docker container
------------------------------

sudo docker rm cifar

To remove the docker image
--------------------------

sudo docker rmi classifier
