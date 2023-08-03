# What is docker?
Docker is a platform or ecosystem around creating and running containers
To have a hello world of sorts in docker we can run the following command in our terminal once we install all docker dependencies: 

    docker run hello-world

When you run this command, docker downloads an image from docker hub and then runs an instance of an image.

## Image
An image is a file with all the deps and config required to run a program

## Container
A container is an instance of an image

To get a better understanding of this concepts we need a quick overview of operating systems theory.





# Why use docker?

When trying to install some software on your personal computer most of the time we follow the next flow in order to get that piece of software up and running on our computer: 

* Download installer
* Run installer 
* <mark>Get an error during installation<mark>
* Troubleshoot issue
* Rerun installer
* Get another error!
And this cycle until we are able to run the program

So essentialy this is what Docker tries to fix. <mark>Docker makes it easy to install and run software without worrying about setup or dependencies<mark>. 
