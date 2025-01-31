# Terraform AWS EC2

## Arguments
ami_id - (Mandatory), user must provide AMI ID.This is in string format
instance_type - (optional), default is t3.micro
security_group_ids - (mandatory), user must provide list of SG ID

## Outputs
public_ip - public_IP of the instance created
private_ip - private_IP of the instance created
instance_id - instance_ID of the instance created