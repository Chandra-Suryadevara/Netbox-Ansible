# Netbox-Ansible
These are scripts or playbooks in ansible to populate data from a csv file into netbox
Certainly! Here's the updated README file with the section on installing Ansible:

```markdown
# NetBox Automation Ansible Playbooks

## Overview

This repository contains a collection of Ansible playbooks designed for automating various tasks related to NetBox, an open-source IP address management (IPAM) and data center infrastructure management (DCIM) tool. These playbooks leverage the NetBox Ansible collection for seamless integration.

## Table of Contents

- [Playbooks](#playbooks)
- [Prerequisites](#prerequisites)
- [Installing Ansible](#installing-ansible)
- [Usage](#usage)
- [Playbook Descriptions](#playbook-descriptions)
- [Contributing](#contributing)
- [License](#license)

## Playbooks

1. **Deleting IPs:**
   - Delete IP addresses in NetBox.

2. **Updating Interfaces:**
   - Update existing interfaces in NetBox.

3. **Deleting Interfaces:**
   - Remove interfaces from devices in NetBox.

4. **Assigning IP to Devices:**
   - Assign IP addresses to devices in NetBox.

5. **Adding Modules:**
   - Add hardware modules to devices in NetBox.

6. **Adding Locations:**
   - Add physical locations to NetBox.

7. **Adding IP Addresses:**
   - Add new IP addresses to NetBox.

8. **Adding Interfaces:**
   - Add new interfaces to devices in NetBox.

9. **Adding Devices:**
   - Add new devices to NetBox.

## Prerequisites

Before using these playbooks, ensure the following prerequisites are met:

- Ansible is installed on the machine where you plan to run the playbooks.
- NetBox instance is accessible and configured properly.
- API token for NetBox is available.

## Installing Ansible

### Linux (Debian/Ubuntu)

1. Update the package index:

   ```bash
   sudo apt-get update
   ```

2. Install Ansible:

   ```bash
   sudo apt-get install ansible
   ```

### Linux (RHEL/CentOS)

1. Enable the EPEL repository:

   ```bash
   sudo yum install epel-release
   ```

2. Install Ansible:

   ```bash
   sudo yum install ansible
   ```

### macOS

1. Install Homebrew if not already installed:

   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

2. Install Ansible using Homebrew:

   ```bash
   brew install ansible
   ```

### Windows

For Windows, Ansible can be installed using Windows Subsystem for Linux (WSL) or a third-party tool like Cygwin. Follow the [official Ansible documentation](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-ansible-on-windows) for detailed instructions.

### Verify Installation

To verify the installation, run the following command:

```bash
ansible --version
```

This should display information about the installed Ansible version.

Now, you are ready to use Ansible to automate tasks with the provided playbooks.

## Usage


1. Edit the playbooks to include your NetBox instance details, such as `netbox_url` and `netbox_token`.

2. Execute the desired playbook using the following command:

   ```bash
   ansible-playbook <playbook_name.yml>
   ```

## Playbook Descriptions

- Each playbook serves a specific purpose, automating tasks related to NetBox.
- Configure NetBox details in the playbooks before execution.
- Review and understand each playbook before running.

## Contributing

Contributions are welcome! If you have improvements or additional playbooks to share, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
```

Feel free to further customize it based on your specific requirements or preferences.
