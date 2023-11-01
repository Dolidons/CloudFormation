aws cloudformation create-stack --stack-name dev-network-infra-pf --template-body file://network_infra.yaml --parameters file://dev_parameter_file.json
aws cloudformation delete-stack \--stack-name dev-network-infra-pf

aws cloudformation create-stack --stack-name dev-network-infra-pf --template-body file://network_infra.yaml --parameters file://dev_parameter_file.json