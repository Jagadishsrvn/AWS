#  AWS VPC Setup with Public & Private Subnets + EC2 Instance

##  Objective
To create a custom VPC with public and private subnets, attach an Internet Gateway, configure routing, and launch a Linux EC2 instance.



##  Steps :
1. Create a VPC (10.0.0.0/16)
2. Create an Internet Gateway and attach to VPC
3. Create two subnets:
   - Public Subnet: 10.0.1.0/24
   - Private Subnet: 10.0.2.0/24
4. Configure route tables and attach to subnets
5. Enable auto-assign public IP in Public Subnet
6. Launch EC2 instance in Public Subnet
7. Connect to EC2 via SSH

- Public Subnet: Internet access available  
- Private Subnet: No direct internet access  
