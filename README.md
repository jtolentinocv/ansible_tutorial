# Update YUM
# yaml file to for ansible-playbook 
---
  - name: updateyum
    hosts: linux
    tasks:
      - name: yum update
        yum:
          name: yum
          state: latest




This is my awesome Ansible repository!
Updated in Git!
