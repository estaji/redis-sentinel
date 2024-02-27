# About
Install Redis-Sentinel based on Docker using Ansible.

# How
Clone this repository, then edit the inventory.ini and vars/config.yaml files.

Consider these requirements:
+ We need 3 identical nodes.
+ Docker should be installed on all nodes.
+ Open Redis and Sentinel ports (6379 and 26379) on all servers.

Then run the playbook:
```
ansible-playbook -i inventory.ini redis-sentinel-on-docker.yaml
```
# Contribution
Feel free and don't hesitate to contribute to this repository.
