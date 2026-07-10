# Infrastructure-Services-and-Operations-Project-1

## Overview

This project demonstrates how Infrastructure as Code can be used to provision and configure a reusable server environment.

Terraform was used to create the virtual machines and network resources in OpenStack, while Ansible was used to install software, configure users and groups, and apply consistent server configurations.

The environment consists of:

- 1 Master Server
- 4 Storage Servers
- 1 Backup Server
- 1 Web Server
- Terraform for infrastructure provisioning
- Ansible for configuration management
- Key-based SSH authentication
- Automated deployment and cleanup scripts

## Technologies

- Terraform
- Ansible
- OpenStack
- Ubuntu Server
- GlusterFS
- Apache2
- PHP
- SSH
- Bash

## Features

- Automated provisioning of virtual machines in OpenStack
- Dynamic creation of four storage servers using Terraform
- Separate Ansible roles for storage, backup, and web servers
- Automated installation of GlusterFS, Apache2, and PHP
- Automated user, group, and sudo configuration
- Key-based SSH access from the master server
- Automated deployment and infrastructure cleanup
- Repeatable and reusable deployment workflow

## Skills Demonstrated

- Infrastructure as Code
- Terraform
- Ansible
- OpenStack
- Linux System Administration
- Configuration Management
- Infrastructure Automation
- SSH Key Management
- Bash Scripting

## Authors

- Ilias Chaoui
- Samatar
