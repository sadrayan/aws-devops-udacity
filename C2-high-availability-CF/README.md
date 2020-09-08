# Create Stack
./create.sh udemy-infra-stack private-network.yml private-network-parameters.json
./create.sh udemy-HA-stack ha-infrastructure.yml ha-infrastructure-parameters.json

# Update Stack
./update.sh udemy-infra-stack private-network.yml private-network-parameters.json
./update.sh udemy-HA-stack ha-infrastructure.yml ha-infrastructure-parameters.json

# Delete Stack




SSH into EC2
ssh -i EC2-KP.pem ec2-user@YOUR_IP

