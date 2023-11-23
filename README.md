# AWS Project - End to End Web application deployment

•	Set up a Virtual Private Cloud (VPC) in AWS
•	Configured subnets within the VPC to define network segments for different components of infrastructure.
•	Established route tables and an internet gateway to enable communication between VPC and the internet
•	Associated the route tables, internet gateway, and subnets to allow proper network traffic flow within my VPC
•	Launched an EC2 instance, which is a virtual server in the AWS cloud
•	Installed the Apache2 web server software on the EC2 instance to host my application
•	Cloned my application's source code from GitHub and moved it to the appropriate directory (/var/www/html) on the EC2 instance. This typically involves deleting the default index.html file.
•	Acquired a domain name from a domain registrar
•	Set up a hosted zone in AWS Route 53 with domain name
•	Obtained the name server (NS) records from the AWS Route 53 hosted zone and updated the domain provider's settings to use those NS records.
•	Added an A record in AWS Route 53 hosted zone to map your domain name to the IP address of your EC2 instance.
•	Browsed Application with the Domain Name
