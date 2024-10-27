# Kali Linux setup with `Ansible`
To feel right at home on a fresh Kali

# Prerequisites
Install `ansible`
```bash
sudo apt install ansible-core
sudo ansible-galaxy collection install community.general # required to set the timezone
```

# Installation
Start the main playbook
```bash
sudo ansible-playbook kali-setup.yml
```
