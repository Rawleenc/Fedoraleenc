# Fedoraleenc

This repository contains my Fedora Workstation post-installation Ansible playbook.

## How to use 

First, install Ansible:
```bash
sudo dnf install ansible
```

Then, run the following command:
```bash
ansible-playbook -K <(curl -L https://raw.githubusercontent.com/Rawleenc/Fedoraleenc/main/local.yml)
```