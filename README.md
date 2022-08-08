# Ansible Network Connectivity

## Run Ansible

### Examples:

```bash
ansible-playbook -i inventories/inventories.yaml --extra-vars @configs/tests.yaml roles/tests.yaml --tags all

ansible-playbook -i inventories/inventories.yaml --extra-vars @configs/tests.yaml roles/tests.yaml --tags tcp
ansible-playbook -i inventories/inventories.yaml --extra-vars @configs/tests.yaml roles/tests.yaml --tags ports

ansible-playbook -i inventories/inventories.yaml --extra-vars @configs/tests.yaml roles/tests.yaml --tags api,verbose
```