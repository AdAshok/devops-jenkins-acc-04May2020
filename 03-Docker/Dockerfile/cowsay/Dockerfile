# Base Image
FROM ubuntu:16.04

# Owner of an Image ( META Info ) 
MAINTAINER Amit Vashist <amitvashist7@gmail.com>

# Update Apt Repo. 
RUN apt-get update 

# Install apache package 
RUN apt-get install cowsay -y 

# Start the Apache Service 
CMD ["/usr/games/cowsay", "Dockerfile is Awesome.!!"]
