# MSR Devops test

CREATED TWO EC2 INSTANCES IN AWS CLOUD 

•	Instance Type: t2.micro

•	Operating System:  Ubuntu Server 16.04 LTS

•	Hostname of Instance 1 : MSR-test-Instance-1

•	Hostname of Instance 2 : MSR-test-Instance-2



Task2:TO INSTALL THE FOLLOWING SOFTWARES I HAVE CREATED AN ANSIBLE PLAYBOOK FILE (REFERE TO THE PLAYBOOK1.YML FILE)

INSTALLED SOFTWARES:

•	NVM – Version 0.33.2

•	Node – 8.12.0

•	Docker – 18.06 or latest

•	Docker Compose – 1.13 or latest

•	Openssl – latest version

•	Git – latest version

launching a new Ec2 machine which is  controlling machine and installing anisible to run the playbook file (Installation.yml)

INSTALLATION STEPS:

    sudo apt-get update

    sudo apt-get install software-properties-common

    sudo apt-add-repository ppa:ansible/ansible

    sudo apt-get update

    sudo apt-get install ansible

After That with Ansible we will run the ansible playbook file.

    ansible-playbook Installation.yml

we have to configure both the hosts in the ansible/host location

It will install all the packages given in the ploybook for above two instances.

Task 3: I have created a index.html file and deployed using anisible playbook file (Deploy.yml)

For running the playbook: ansible-playbook Deploy.yml

Task 4:I have created a Database.yml file which will install the CouchDB Database and runs the service. 

for running the playbook: ansible-playbook Database.yml

 I have tried all the above tasks which were given for the test.
 




