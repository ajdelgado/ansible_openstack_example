# ansible_openstack_example
Sample repository on how to spin up servers in Openstack using Ansible

## Requirements
- You will need a file called *vault_password* in the root with the password in clear text of your Ansible Vault
- Ansible
- Galaxy collection openstack.cloud (Run *ansible-galaxy collection install openstack.cloud* from the root of the repository to get it installed)

## Running it

ansible-playbook playbooks/spinup_nodes.yml

## References
### Installing Ansible
https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html

### Module to manage servers (virtual machines)
https://docs.ansible.com/ansible/latest/collections/openstack/cloud/server_module.html#ansible-collections-openstack-cloud-server-module

### List of modules to manage Openstack resources
https://docs.ansible.com/ansible/latest/collections/openstack/cloud/index.html