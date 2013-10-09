Ansible Install Examples
=====================
This is a collection of examples of different configurations of the Install Scripts for OpenShift Enterprise

- These example require [ansible](http://www.ansibleworks.com/docs/intro_installation.html) to be installed. 

Once installed you can use the provided examples to setup and configure OpenShift Enterprise. 
- *currently thise examples use KVM*

**Example**: (create an all in one OpenShift system). 
```
ansible-playbook plays/all_in_one.yml -i inventory
```

**Example**: (create a destributed OpenShift Enviornment). 
```
ansible-playbook plays/enviornment.yml -i inventory
```
