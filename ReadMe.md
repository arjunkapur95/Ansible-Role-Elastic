# Changes needed on control machine
es_enable_xpack: false 

# Steps For Configuring Control
* sudo yum update && sudo yum -y install git
* mkdir roles
* cd roles
* git clone https://github.com/arjunkapur95/Ansible-Role-Elastic.git
* Finally Create Your Executable Yaml which points to roles/Ansible-Role-Elastic
