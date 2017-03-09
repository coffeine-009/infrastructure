Infrastructure setup. Ansible configuration
==============================================

Getting Started
-----------------------------------
### Install ci.jenkins role
```bash
ansible-galaxy install geerlingguy.jenkins -p roles
```

```bash
ansible-playbook -u root --sudo --ask-sudo-pass -i production site.yml
```

