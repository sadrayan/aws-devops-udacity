# Create Stack
./create.sh udemy-infra-stack private-network.yml private-network-parameters.json
./create.sh udemy-HA-stack ha-infrastructure.yml ha-infrastructure-parameters.json
./create.sh udemy-bastion-host-stack bastion-host.yml ha-infrastructure-parameters.json

# Update Stack
./update.sh udemy-infra-stack private-network.yml private-network-parameters.json
./update.sh udemy-HA-stack ha-infrastructure.yml ha-infrastructure-parameters.json
./update.sh udemy-bastion-host-stack bastion-host.yml ha-infrastructure-parameters.json

# Delete Stack
./delete.sh udemy-bastion-host-stack
./delete.sh udemy-HA-stack
./delete.sh udemy-infra-stack




SSH into EC2
ssh -i EC2-KP.pem ec2-user@YOUR_IP

