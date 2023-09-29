# lamp_setup-Ansible
Setting Up a Server having Lamp Setup through Ansible.

#### to check your node ping

```
ansible all -m ping -i lamp.hosts
```
#### to run the playbook
```
ansible-playbook lamp.yml -i lamp.hosts
```
