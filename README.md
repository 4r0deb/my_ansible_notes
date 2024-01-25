# my_ansible_notes

Execute the command:

ansible-playbook -i inventory.ini p4.yaml -u i4t --ask-pass

ansible all -m shell -a 'uptime -p' --ask-pass
ansible all -m shell -a 'ls -l' --ask-pass
