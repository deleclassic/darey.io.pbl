
# WEB STACK IMPLEMENTATION (LEMP STACK)

## LINUX + NGINX + MYSQL + PHP

Project 2 helps us cement the skills of deploying Web Solutions using LEMP Stacks, in Project 1 we use the Apache2 Web server while project 2 will be using the Nginx web server which is also popular and widely used as Apache

## 1. Setting a virtual webserver (EC2) with Ubuntu OS using the free tier T2.micro family of instances and Connecting to NGINX WEB Server

In order to display web pages to our site visitors, we are going to employ Nginx, a high-performance web server. We’ll use the apt package manager to install this package. Since this is our first time using apt for this session, start off by updating your server’s package index. Following that, you can use apt install to get Nginx installed:

Download, install Git Bash, launch and run following command

ssh -i "cohort-two-key.pem" ubuntu@ec2-3-8-187-200.eu-west-2.compute.amazonaws.com
