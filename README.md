# Project2
UDACITY Project 2 Repo

http://proje-webap-1mdweypn1lcq3-1502256266.us-west-2.elb.amazonaws.com/

#Rubrics

# The Basics
# Parameters The more the better, but an exaggerated number of parameters can be messy ( say, 10 or more ). 1 or 0 is definitely lacking. =yes
# Outputs This is optional, but it would be nice to have a URL here with the Load Balancer DNS Name and “http” in front of it . =yes
# This is the mandatory section of the script, we are looking for a LoadBalancer, Launch Configuration, AutoScaling group a health check, security groups and a Listener and Target Group. = yes
# working test If the student provides a URL to verify his work is running properly, it will be a page that says “it works! Udagram, Udacity”
# Load Balancer 
# Health Check and Listener Port 80 should be used in Security groups, health checks and listeners associated with the load balancer = yes
# Target Group The auto-scaling group needs to have a property that associates it with a target group. The Load Balancer will have a Listener rule associated with the same target group = yes
# Auto-Scaling
# Subnets Students should be using PRIV-NET ( private subnets ) for their auto-scaling instances  = yes
# Machine Specs The machine should have 10 GB or more of disk and should be a t3.small or better. = yes
# SSH Key There shouldn’t be a ‘keyname’ property in the launch config = yes
# Bonus Any values in the output section are a bonus = yes
