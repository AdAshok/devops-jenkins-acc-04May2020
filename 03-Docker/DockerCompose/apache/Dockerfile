# Base Image
FROM ubuntu:16.04

# Owner of an Image ( META Info ) 
MAINTAINER Amit Vashist <amitvashist7@gmail.com>

# Update Apt Repo. 
RUN apt-get update 

# Install apache package 
RUN apt-get install apache2 -y 

# Deploy Custom Index Page
COPY index.html /var/www/html/index.html
COPY cow.html /var/www/html/cow.html

# Expose Port
EXPOSE 80

# Start the Apache Service 
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
