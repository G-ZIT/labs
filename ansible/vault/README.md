## Ansible Vault

Most of the times when sensitive or confidential data need to be protected in the playbook, then it can be encrypted rather than just keeping it in a text file which is readable by all. Ansible Vault allows you to encrypt the playbook to protect the confidential data.

1) ansible-vault create jobagreement.yml

2) ansible-vault encrypt existingfile.yml

3) ansible-vault view jobagreement.yml

4) ansible-vault edit users.yml

5) ansible-vault rekey jobagreement.yml

6) ansible-playbook users.yml --ask-vault-pass

7) ansible-vault decrypt jobagreement.yml

