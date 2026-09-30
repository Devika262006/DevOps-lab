# Experiment 4 – Ansible YAML Playbook Automation

## Aim

To write and execute a simple YAML file containing variables and tasks in Ansible, and automate system tasks.

## Software / Requirements

- Ubuntu 24.04 LTS / WSL2
- Python 3
- Ansible
- Terminal

## Files

- `hosts.ini` – Ansible inventory file
- `setup.yml` – Ansible YAML playbook

## Inventory

The inventory defines localhost as the managed host using a local Ansible connection.

## Playbook Tasks

The playbook performs the following tasks:

1. Creates the `/tmp/devops_lab` directory.
2. Creates `message.txt` inside the directory.
3. Displays the completion message.

## Commands Executed

```bash
ansible --version
ansible-inventory -i hosts.ini --list
ansible-playbook -i hosts.ini setup.yml --syntax-check
ansible-playbook -i hosts.ini setup.yml
