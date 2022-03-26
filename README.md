### Project Title - Deploy a high-availability web app using CloudFormation
    1- Deploy a VPC
    2- Public and pair of private subnets spread across two Availabilty Zones.  
    3- Deploy an Internet Gateway, with a default route on the public subnets. 
    4- Deploys a NAT Gateways and default routes for them in the private subnets.
    5-You have to consider creating keyparis with the name "nd9990_keypair"
    6-Build the load balance and the target group
    7-Output the URL of the loadbalancer and here you go!
### ############       rubrics    ####################################
Parameters                      6 and most of them related to the network and only one for environment name
Resources                       All of required are covered
Outputs                         VPC ID and the Url of Loadbalancer with "http://"
### ############       Load Balancer    ##############################
Target Group                    Done
Health Check and Listener       Port 80 is used as required
### ############       Auto-Scaling    ###############################
Subnets                         Private Subnet is used for autoscaling instances
Machine Specs                   10 GB or more of disk and t2.medium
SSH Key                         No keyname is used
### ############       Bonus    ###############################
Output                          Both VPCid and loadbalancer URL
Bastion Host                    NA


