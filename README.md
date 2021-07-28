# ansible-tutorial


## Install Ansible
      sudo apt install apache2


## Plays

### Hello World
      ansible-playbook -i inventory/hosts.yml helloworld.yml

### Updates
      ansible-playbook -i inventory/hosts.yml updates.yml

### Webserver (Apache2)
      ansible-playbook -i inventory/hosts.yml webserver.yml


## Ad-Hoc Example
      ansible -i inventory/hosts.yml all -m ping


