# ansible-playbook - basic setup

Ansible playbook that creates a wheel user.
Also updates packages and installs git.

## Instructions

1. Install ansible-playbook
2. Create a hosts file with your target host
3. Run the playbook in the project directory:

```
ansible-playbook -i hosts -u root main.yml
```

