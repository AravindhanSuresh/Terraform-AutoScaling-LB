Tasks:
Deploy a VPC with custom CIDR
Create 2 public subnets and 2 private subnets with custom CIDRs — where private subnets are used for compute instances running webservers & public subnets are used by application load balancers
Create the autoscaling group with AWS AMI and user data to install and start the Nginx server
Create volumes for the instances in ASG to store application & log data
Prerequisites:
AWS account
IAM role with necessary permissions
Terraform & AWS CLI configured on the machine from which the scripts are to be run
