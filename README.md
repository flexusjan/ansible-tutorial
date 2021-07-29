# Ansible Tutorial


## Install Ansible
      sudo apt install ansible

## Ansible Version
2.9

## Example Playbooks

### Hello World
      ansible-playbook -i inventory/hosts.yml helloworld.yml

### Updates
      ansible-playbook -i inventory/hosts.yml updates.yml

### Webserver (Apache2)
      ansible-playbook -i inventory/hosts.yml webserver.yml


## Ad-Hoc Example
      ansible -i inventory/hosts.yml all -m ping

### Documentation

## Ansible Builtin Modules
https://docs.ansible.com/ansible/latest/collections/ansible/builtin/index.html

## Ansible Inventory Guide
https://docs.ansible.com/ansible/2.9/user_guide/intro_inventory.html

## Ansible Roles
https://docs.ansible.com/ansible/2.9/user_guide/playbooks_reuse_roles.html

## Ansible Variables
https://docs.ansible.com/ansible/2.9/user_guide/playbooks_variables.html

## Ansible Templating (Jinja2)
https://www.digitalocean.com/community/tutorials/how-to-create-and-use-templates-in-ansible-playbooks

## Ansible Explained (TechWorld with Nana)
https://www.youtube.com/watch?v=1id6ERvfozo
