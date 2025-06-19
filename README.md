# yaml-have-fun
Cloudformation stack with Parameters (variables)


#Create an ec2 instance with the name application-server
#The server should be a windows-2022 server
#The server should be a t2 micro
# It should be hosted in the Northern Virginia
# It should be connected to the VPC my-vpc, but we want to choose the vpc on launching.
# The server clock should be set to EasternStandard Time
# tag #development, but it could be production or qa as well. This should be enforced on launching.
# The server needs access to a SQL Server

CloudFormation STEP 1:


CloudFormation STEP 2:
specify Parameters

- select inbound cidr range
- instance type
- SG description
- VPC
- Subnets 1 and 2 cidr range
  
Avail Subnet  Research
Used >>>  172.31.164.0/24,172.31.165.0/24