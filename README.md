# ansible-homelab

Based on ansible-homelab by [TechnoTim](https://github.com/timothystewart6)

## Usage

```
ansible-playbook ./playbooks/docker-config.yml --user ubuntu --ask-pass --ask-become-pass -i ./inventory/hosts.ini
```