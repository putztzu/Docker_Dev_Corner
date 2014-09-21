Docker_Dev_Corner
=================

Collection of Docker commands specific to and useful for building

A container not running. To create a new container and display the stdout before the container expires run the following

id=$(docker run ...); docker logs $(id)
