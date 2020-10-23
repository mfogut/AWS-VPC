This CloudFormation template will automate VPC and some other AWS resources.

- 1-Virtual Private Cloud created (VPC) "vpc1". Line 16-25
- 2-Public Subnet created for vpc1. Line 26-35
- 3-Private Subnet created for vpc1. Line 36-45
- 4-Internet Gateway created for vpc1. Line 46-52
- 5-Internet Gateway attached to vpc1. Line 53-59
- 6-Public Route Table created for vpc1 Public Subnet. Line 60-66
- 7-Route added to Public Route Table to open Public Subnet to internet. Line 67-75
- 8-Subnet Association added to Public Route Table. Line 76-82
- 9-Private Subnet Route Table created/ Line 83-89
- 10-NAT Gateway created in Public Subnet to open Private Subnet to internet and AWS services. Line 90-97
- 11-Elastic IP allocated. Line 98-101
- 12-Route added to Private Route Table to open Private Subnet to internet via NAT Gateway. Line 102-109
- 13-Subnet Association added to Private Route Table. Line 110-116
- 14-Virtual Private Cloud created (VPC) "vpc2". Line 117-126
- 15-Public Subnet created for vpc2. Line 127-137
- 16-Private Subnet created for vpc2. Line 138-147
- 17-Internet Gateway created for vpc2. Line 148-154
- 18-Internet Gateway attached to vpc1. Line 155-161