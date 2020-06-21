



The dependent roles for tomcat jenkins and nexus are in below respositories .
Clone them and add the path to ansible.cfg

Repositories:
https://github.com/Revathi-Santhosh/ansible-modules.git


# ROLES PATH
For example i have added roles path for tomcat8 which is in ~/personal/ansible-modules/roles. Here anisble checks for roles in path `roles/`  in current directory if the roles are not found in current directory roles path then it looks for  roles in ~/personal/ansible-modules/roles directory. We can provide any number for roles path and ansible checks in order
roles_path = roles:~/personal/ansible-modules/roles:/etc/ansible/roles
