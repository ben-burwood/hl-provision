# Provisioning

## Ansible

Install Ansible Core with apt (`apt install ansible-core`) and any other dependencies (maybe 'sshpass')

`ansible-galaxy install -r requirements.yml`

Run with `ansible-playbook -i inventory provision.yml`
