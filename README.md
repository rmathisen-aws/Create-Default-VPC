# Create Default VPC

VPC → Virtual Private Cloud → Your VPCs

Default VPCs: \
1 per Region \
Default VPC CIDR is always 172.31.0.0/16 \
/20 Subnet in **each AZ** in the Region \
Provided with a Internet Gateway (IGW), Security Group & Network ACL (NACL)

Notice the number of Subnets, with their allocated IPv4 CIDR blocks, change based on the Region you have selected!

\
If VPC is deleted, or if any of the provided components are, and you want to \
**Create Default VPC:** \
VPC → Virtual Private Cloud → Your VPCs \
Actions → Create Default VPC
