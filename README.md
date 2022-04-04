
# Requriments to use playbook

1.	Install Ansible
2.	Install Boto3
3.	Setup env variables for AWS (AWS_SECRET_ACCESS_KEY=xxx , AWS_ACCESS_KEY_ID=xxx ) 
4.	In file ./group_vars/main_server  define path to ssh private key - ansible_ssh_private_key_file : "path/"
5.  run 'ansible-playbook wp_on_lemp_playbook.yml --ask-vault-pass "your password"'
6.  Profit!!!