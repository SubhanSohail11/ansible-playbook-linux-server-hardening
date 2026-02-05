# Linux Server Hardening with Ansible

This playbook applies a set of security hardening steps to a Linux server and creates a privileged user named **subhan**. It installs common security tools, configures SSH securely, enables a firewall, and sets up automatic updates. The goal is to provide a solid baseline for a secure server setup without adding unnecessary complexity.


- Creates user **subhan** and grants sudo access  
- Installs and configures:
  - Fail2ban  
  - UFW firewall  
  - Unattended security upgrades  
- Disables root SSH login  
- Disables password authentication  
- Installs your SSH public key for secure access  
- Enables automatic updates  
- Applies basic SSH and fail2ban hardening

