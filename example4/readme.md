ansible-playbook master.yaml -i inventory.ini -u root

implement tags:

only tasks with tag 'first tag'
ansible-playbook master.yaml -i inventory.ini -u root --tags=first\ tag

not tasks with tag 'first tag'
ansible-playbook master.yaml -i inventory.ini -u root --skip-tags=first\ tag