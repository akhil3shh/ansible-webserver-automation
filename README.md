# Webserver Automation using Ansible 

This project demonstrates horizontal scaling of web servers using Ansible using Round Robin algorithm for   
load-balancing, HAProxy as reverse proxy (frontend webserver) and Apache's HTTP as backend server.

# Major Steps to follow: 
1.) Create 5 AWS EC2 t2.micro instances - one for Ansible Controller node, one for the load-balancer and remaining three for
the web servers.    
2.) Install required dependencies on the instances and update the instances.  
3.) Edit the inbound rules so that all these instances are accessible.   
4.) Write down the YAML configuration files for the load-balancer and webservers, a simple PHP webpage for HTTPD webserver 
and a template configuration file for HAProxy (used for registering webservers).  
5.) Finally, deploy your webpage and all webservers and check if the load-balancer is functioning properly.  

