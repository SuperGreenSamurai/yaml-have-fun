# yaml-have-fun
Cloudformation stack with Parameters

1. Create an ec2 instance with the name application-server

2. The server should be a windows-2022 server

3. The server should be a t2 micro

4. It should be hosted in the Northern Virginia

5. It should be connected to the VPC my-vpc, but we want to choose the vpc on launching.

6. The server clock should be set to Eastern Standard Time

7. tag #development, but it could be production or qa as well. This should be enforced on launching.
   
8. The server needs access to a SQL Server

CloudFormation STEP 1:
![CF-yaml-step1](https://github.com/user-attachments/assets/d9142101-c104-4615-82f3-3d2bdc2e9997)



CloudFormation STEP 2:
specify Parameters
- select inbound cidr range
- instance type
- SG description
- VPC
- Subnets 1 and 2 cidr range

![CF_step3](https://github.com/user-attachments/assets/d1db2883-fed7-4357-9213-1226bcd84770)
  
Subnet Research
Used >>>  172.31.164.0/24,172.31.165.0/24
![networking-range](https://github.com/user-attachments/assets/8f990d48-353c-4669-92d1-edbe873d2038)

Completions
![CF_completion](https://github.com/user-attachments/assets/4c722856-189f-4261-a718-20846b14760a)
