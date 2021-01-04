# CloudFormationChallenge
Using CloudFormation, create the following infrastructure in AWS -  
Create a custom VPC with three private subnets and three public subnets. 
Create an application load balancer to serve traffic web between two EC2 instances.
You must use a custom AMI Deploy a VPN server to ssh from home to the EC2 instances.


# Set up VPN
connect to your instances with ec2 with ssh with the key 
after you change the passwod with the next command
- passwd openvpn
- set the new password
Then select your public ip and paste https://publi-ip:943/admin
user: openvpn
password: [yourPassword]
Then go to Network Settings, in the textbox (Hostname or IP Address) put ypur public ip 
Then download application with https://publi-ip