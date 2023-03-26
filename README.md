# -terraform-ec2-clone
 
git clone https://github.com/awssabil/-terraform-ec2-clone.git

edit vars.tf using this command ->  vim vars.tf
edit variables of region, ami-name,Key-pair accordingly
and run -
terraform init
terraform plan
terraform apply

If everything is done well.  Now sit back and relax for few minutes a new AMI would be created from the source instance which would be used to create a new EC2 instance

The new EC2 instance (clone EC2 instance) would have the same instance type , VPC ID and security group configuration.
