# Ansible OpenVPN

## Roles & Tags

### Tags

#### API:

- api
- verbose (print response)

#### TCP:

- tcp

#### Ports:

- ports

## Run Ansible

### Examples:

```bash
ansible-playbook -i inventories/inventories.yaml --extra-vars @configs/tests.yaml roles/tests.yaml --tags api,verbose
ansible-playbook -i inventories/inventories.yaml --extra-vars @configs/tests.yaml roles/tests.yaml --tags ports
ansible-playbook -i inventories/inventories.yaml --extra-vars @configs/tests.yaml roles/tests.yaml --tags tcp
ansible-playbook -i inventories/inventories.yaml --extra-vars @configs/tests.yaml roles/tests.yaml --tags all
```