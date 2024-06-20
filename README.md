# Ansible Beginner Projects

Welcome to the Ansible Beginner Projects repository. This repository contains a series of beginner-level projects designed to help you solidify your knowledge of Ansible, a powerful configuration management and automation tool. Each project is organized into its own folder, and this README file provides an overview of the contents and goals of each project.

## Project Structure

- **01_Basic_Setup_and_Inventory_Management**
  - **Description:** Learn how to install Ansible, create an inventory file, and use Ansible ad-hoc commands to manage hosts.
  - **Contents:** 
    - `inventory`: Inventory file with host definitions.
    - `setup.md`: Instructions and outputs of the basic setup and ad-hoc commands.

- **02_Simple_Playbook_Creation**
  - **Description:** Create a simple playbook to install a web server (Apache/Nginx) on a remote host.
  - **Contents:** 
    - `install_web_server.yml`: Ansible playbook to install and start a web server.
    - `output.md`: Execution logs and verification steps.

- **03_Configuration_Management**
  - **Description:** Manage configuration files using Ansible, including deploying templates and validating configurations.
  - **Contents:** 
    - `configure_web_server.yml`: Playbook for deploying and managing web server configurations.
    - `templates/`: Directory containing Jinja2 templates for configuration files.
    - `output.md`: Execution logs and validation steps.

- **04_Package_Management**
  - **Description:** Automate the installation of multiple packages and ensure idempotency.
  - **Contents:** 
    - `install_packages.yml`: Playbook to install specified packages.
    - `output.md`: Logs showing the execution and package installation verification.

- **05_User_and_Permission_Management**
  - **Description:** Automate user creation, group management, and permission settings.
  - **Contents:** 
    - `manage_users.yml`: Playbook for managing users and permissions.
    - `output.md`: Logs and evidence of user creation and permission settings.

- **06_Service_Management**
  - **Description:** Ensure that specific services are running and enabled at boot using Ansible.
  - **Contents:** 
    - `manage_services.yml`: Playbook for managing services.
    - `output.md`: Logs showing service status before and after playbook execution.

- **07_Deploying_Applications**
  - **Description:** Deploy a simple web application and ensure it is running correctly.
  - **Contents:** 
    - `deploy_application.yml`: Playbook for deploying a web application.
    - `app_files/`: Directory containing the web application files.
    - `output.md`: Logs and verification steps showing the application is running.

- **08_Playbook_Optimization_and_Best_Practices**
  - **Description:** Refactor and optimize playbooks for readability, efficiency, and best practices.
  - **Contents:** 
    - `optimized_playbooks/`: Directory containing refactored playbooks.
    - `roles/`: Directory for Ansible roles.
    - `output.md`: Explanation of changes and optimization steps.

- **09_Using_Ansible_Vault**
  - **Description:** Secure sensitive data using Ansible Vault and manage encrypted variables.
  - **Contents:** 
    - `vault_playbook.yml`: Playbook demonstrating the use of Ansible Vault.
    - `vault_vars/`: Directory containing encrypted variable files.
    - `output.md`:
