
# WEB STACK IMPLEMENTATION (LAMP STACK) IN AWS

A technology stack is a set of frameworks and tools used to develop a software product. This set of frameworks and tools are very specifically chosen to work together in creating a well-functioning software. They are acronymns for individual technologies used together for a specific technology product. some examples are LAMP, LEMP, MERN and MEAN

## LAMP STACK set up involve setting up (Linux + Apache + Mysql + PHP)

## 1. Set up AWS account and spin up an EC2 Instance (LINUX Server)
![Text1 AWS](https://github.com/deleclassic/darey.io.pbl/assets/134456810/5bc5335f-af41-4ac7-b9b2-90d762ca3931)
connect to the EC2 terminal using Ubuntu installed on Windows 11 by ssh the setup looks like this
![Text2 AWS](https://github.com/deleclassic/darey.io.pbl/assets/134456810/990b5202-3b89-4a09-8c26-89e6963e3919)

## 2. installing apache and updating the firewall

APACHE HTTP SERVER is the most widely used web server software. Developed and maintained by Apache Software Foundation, Apache is an open source software available for free. It runs on 67% of all webservers in the world. It is fast, reliable, and secure. It can be highly customized to meet the needs of many different environments by using extensions and modules. Most WordPress hosting providers use Apache as their web server software. However, websites and other applications can run on other web server software as well. Such as Nginx and Microsoft IIS

Now, Install Apache using Ubuntu’s package manager 'apt'

`sudo apt update`

run apache2 package installation

`sudo apt install apache2`

To verify that apache2 is running as a Service in my OS, i used following command

`sudo systemctl status apache2`

Please Note, if the apache2 is correctly install it will show green and running, I have just launched my first Web Server in the Clouds
