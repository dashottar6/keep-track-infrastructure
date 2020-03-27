# Infrastructure

Here we use the template build body and create/delete/update stack We can even use seperate file to send parametes which helps in saving sensitive data

## create stack

aws cloudformation create-stack --stack-name "stack_name" --template-body file://path/to/file_location/network.json

## delete stack

aws cloudformation delete-stack --stack-name "stack_name"

## update stack

aws cloudformation update-stack --stack-name "stack_name" --template-body file://path/to/file_location/network.json

add --profie while using aws



Configuration of 3 subnets

RDS also added to infrastructure

s3 bucket configured which runs on t3.micro