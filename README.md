# Cloudformation cross stack refence

## Steps

- Create a stack for the VPC.yaml template
- The name for the VPC Stack must be recorded for cross reference on EC2 Stack
- Create a stack for the EC2-instance.yaml and for the param `NetworkStackName`, give VPC's stack name that you create from VPC.yaml template
