# terraform aws ec2

# arguments
ami_id - (mandatory), user must provide ami_id this is in string format
instance_type - optional, default is t3.micro
security_group_ids - (mandatory), user must provide list of sg id

## outputs
public_ip - public ip of the instance created
private_ip - private ip of the instance created
instance_id - instance_id of the instance created