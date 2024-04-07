# Ansible Playbook: Change Hostname

This Ansible playbook is used to change the hostname of the target host(s) using the `hostnamectl` command.

## Prerequisites

- Ansible installed on your local machine.
- SSH access to the target host(s) configured for passwordless authentication.

## Instructions

1. Clone this repository to your local machine:

```bash
git clone <repository-url>

2. Change directory:
   
   ```bash
   cd <playbook-directory>
3. Run playbook:
   
   ```bash
   ansible-playbook -i <path-to-inventory-file> <path-to-playbook-file>
