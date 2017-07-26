#  HA Load-Balanced Web Servers

The AWS Cloudformation template will provision a Elastic Load Balancer and 2 http web server that will display the Server Hostname and the Instance ID. This configuration provides High-Availabity for the webservers and also auto-heals. A database connection test is also done by index.php file. The Web Servers will be install Apache server, PHP and Puppet.

Instructions
============

User should provide Puppet server Hostname and IP address so that Webserver will be act as agents to the Puppet server for any further deployment. 

Functions
=========
HA HTTP servers

Webpage that displays the Server Hostname and Instance ID

HTTP-HTTPS redirection

Connection Test to Database
