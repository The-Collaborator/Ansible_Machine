# Ansible_AWS_Project

 This project uses the DevOps tool, Ansible, to deploy a website on multiple Amazon Web Services(AWS) EC2 instances. 
 Initially, an 'Ansible Machine' comprised of one instance was launched. A key pair on the Ansible Machine was then created. This key pair was used to establish an ssh connection between the Ansible Machine and the multiple servers to come. In order to complete the connection architecture; a security group was created which allowed ssh access between the Ansible Machine and the multiple servers. 
 There after, for the successful deployment of the website using Ansible, three elements were created: 
 # An Ansible playbook which contains a list of commands (tags) ran on the servers.
# An inventory file which contains the private IP address of the instances configured in order to execute the playbook.
# An ansible configuration file which contains the configuration assets used during the runtime.
