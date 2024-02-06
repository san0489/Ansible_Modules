# Ansible_Modules
Installation:

Linux:

sudo apt update

sudo apt install ansible

sudo yum install epel-release

sudo yum install ansible

MAC:

brew install ansible

Authentication:

I prefer passing password every time to run the playbooks. That said, I pass my ssh username in the hosts file.

**Hosts file **

SAN:
test1san.com ansible_ssh_user=snalam
test2san.com ansible_ssh_user=snalam


While running the command use the below and it prompts for your password

ansible-playbook -i hosts playbookname.yml -kK

k : For your ssh username/passowrd

K : For root username/password


