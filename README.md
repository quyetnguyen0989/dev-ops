# dev-ops
Run ansible-playbook for install services


In Ansible:
# ansible -i host -u root -m ping all
# ansible -i hosts -u root -m shell -a 'date' webservers
# ansible -i hosts -u root -m shell -a 'sudo apt-get update'  webservers
# ansible-playbook -i hosts -u root nginx.yml   | in stall nginx on webservers
# sudo apt-get update && sudo apt-get install python-pip | install python
# sudo pip install boto awscli   | install library aws
