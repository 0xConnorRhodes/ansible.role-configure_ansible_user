# Ansible Role: Configure Ansible user
*role to configure ansible user on a VPS to allow future plays to be run as the ansible user*

### outline
1. test that root user can be SSHed into (using password supplied in the the VAR file)
2. then ssh and gather facts and create the ansible user (with no password)
3. copy ansible ssh key to ansible user
4. make sure the ansible user can access it's own authorized keys file

### misc:
- depends on the gnu pass thing
