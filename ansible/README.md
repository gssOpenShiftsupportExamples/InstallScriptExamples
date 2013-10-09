Ansible Install Examples
=====================
This is a collection of examples of different configurations of the Install Scripts for OpenShift Enterprise

- These example require [ansible](http://www.ansibleworks.com/docs/intro_installation.html) to be installed. 

Once installed you can use the provided examples to setup and configure OpenShift Enterprise. 

To get started you will need to set up an SSH key between you and the Hypervisory (I use localhost). 

```
ssh-keygen
sudo cat ~/.ssh/id_rsa.pub >> /root/.ssh/authorized_keys
```

- *currently thise examples use KVM*

**Example**: (create an all in one OpenShift system). 
```
ansible-playbook plays/all_in_one.yml -i inventory
```

**Example**: (create a destributed OpenShift Enviornment). 
```
ansible-playbook plays/enviornment.yml -i inventory
```
