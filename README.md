# dev-env-ansible
Deployment script for TLI development environment

## Requirements
- Ansible (Tested with 2.15.2)

## Usage
```
ansible-playbook -i hosts -u [USER] dev-env.yml
```

where `hosts` is your inventory file and `[USER]` is the user you want to connect as.
