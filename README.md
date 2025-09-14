# Midterm Practical – Firewall Configuration with Ansible

This repository contains the **Midterm Examination (Practical)** from **CPE 213-CPE32S21 - Cloud Management and Security**. It demonstrates **Ansible automation** for configuring firewalls on **Ubuntu and CentOS servers**, simulating real-world **enterprise network security tasks**.

## Overview
Implemented **security automation** for Linux systems using Ansible, focusing on:

- Installing and enabling firewalls (UFW for Ubuntu, firewalld for CentOS)
- Configuring SSH access rules
- Applying consistent security policies across different Linux distributions

Automation reduced manual intervention, ensured compliance, and minimized configuration errors.

## Key Tasks
- Applied OS-specific roles for Ubuntu and CentOS.
- Installed and started `ufw` on Ubuntu and `firewalld` on CentOS.
- Configured firewall rules to allow SSH connections.
- Ensured services are enabled and persistent across reboots.

## Simulation Environment
- VirtualBox with Ubuntu and CentOS nodes
- One node as **Ansible control**, others as **managed hosts**
- Tasks executed via **playbooks and roles** for OS-specific configurations

## Skills & Tools
Ansible | Linux (Ubuntu/CentOS) | Firewall Management (UFW/firewalld) | Security Automation | Playbooks & Roles

## Reflections
This practical demonstrated how **Ansible can streamline firewall management**, enforce security policies consistently across multiple OSes, and reduce human error. It reinforced the importance of **automation in enterprise security operations**.
