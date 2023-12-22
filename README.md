# Configuration of development machine using Ansible Playbooks

## Overview

This repository contains an Ansible playbook for configuring my development machines. The playbook automates the installation and configuration of various software and settings to set up my development environment. 

## Prerequisites

Before running the playbook, ensure that the following prerequisites are met:

1. **Ansible Installed:** Make sure Ansible is installed on your machine. You can install Ansible by following the instructions in the [official documentation](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).

2. **Ansible Galaxy Roles:** The playbook relies on external roles from Ansible Galaxy. You can install these roles using the `requirements.yml` file.

## Usage

### Step 1: Clone the Repository

```bash
git clone https://github.com/chilluxer/ansible_configurations
cd ansible_configuration
```

### Step 2: Install Ansible Galaxy Roles

Use the following command to install the roles defined in the `requirements.yml` file:

```bash
ansible-galaxy install -r requirements.yml
```

### Step 3: Run the Ansible Playbook

Execute the Ansible playbook to configure your laptop:

```bash
ansible-playbook main.yml
```

## License

This project is licensed under the [MIT License](LICENSE).
