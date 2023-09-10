# CMPE_272_Ansible_CodeHeist
Contains Documentations, Ansible playbooks to deploy and un-deploy webserver resources on AWS

## hosts
contains slaves public IP under group names vm1, vm2

## deploy_book.yml
ansible playbook to create and start apache servers in vm1, vm2. 
Also has task to create HTML file on vm1, vm2.

## undeploy_book.yml
ansible playbook to undeploy apache servers in vm1, vm2. 
Also has task to delete HTML file on vm1, vm2.

## ansible.cfg
Default config file created during ansible installing

## CMPE_272_Ansible_CodeHeist_Docu.pdf
Step by step guide to 
1. install ansible
2. create ssh key
3. add ssh key to slaves
4. ssh into the slaves from master ec2 instance
5. ansible install and ping slaves from master
6. ansible deploy servers on slaves from master using ansible playbook and verify the same on webpage created
7. ansible undeploy servers on slaves




