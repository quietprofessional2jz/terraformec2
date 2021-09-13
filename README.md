# terraformec2
Use terraform to spin up an EC2 server (linux)  for use 

'''part I''' 

infra inventory: 

1 public VPC 

1 private VPC  

1 internet gateway 

(other neting components as needed) 

1EC2 server (linux)  

1 EBS volume  

'''all AWS resource should have tags(metadata) which displays the following: '''

1. Creation Timestamp 

2. User which created the resource 

3. Time-To-Live(e.g TTL=4d or TTL =80m or TTL=1(permanent)) 

4. The commit hash from the repo where this config is defined. 

Users should be able to access the EC2 server via  ssh over a nonstandard port (such as 9022/ AKA not 22)  

Deployment of this terraform should be automated via bash and/or Python 
