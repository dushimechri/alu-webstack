HTTPS SSL Project
This project involves configuring a load balancer (HAProxy) and web servers (Nginx) for a high-availability web application with SSL/TLS encryption.

Learning Objectives
By the end of this project, you will be able to:

Explain what HTTPS and SSL are and their two main roles.
Understand the purpose of encrypting traffic.
Explain what SSL termination means.
Tasks
Task 0: World Wide Web
Configure DNS records for www, lb-01, web-01, and web-02.
Write a Bash script (0-world_wide_web) to display DNS information.
Task 1: HAProxy SSL Termination
Install Certbot and generate an SSL certificate for www.ssdsolutions.tech.
Configure HAProxy to handle HTTPS traffic.
Test HTTPS access to the website.
Task 2: Redirect HTTP to HTTPS
Configure HAProxy to redirect HTTP traffic to HTTPS.
Test HTTP-to-HTTPS redirection.
