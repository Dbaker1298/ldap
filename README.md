# ldap
LDAP server for cental authentication

## Assumptions

- Ansible installed on control node (localhost in my case)
- Python version 3.13.x or greater installed
- Python `pip` version 24.2 or greater installed
- `vultr-python` SDK `pip install vultr-python`
- SSH key added to your Vultr account

## Install on Control Node

1. Install Vultr SDK: `pip install vultr-python`
2. Verify the Vultr API is available locally; `export VULTR_API_KEY='xxx'`
3. Install Vultr Ansible collection: `ansible-galaxy collection install -r requirements.yaml
