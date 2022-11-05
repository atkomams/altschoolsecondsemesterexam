# Altschoolsecondsemesterexam
My altschool second semester exam project - Deploy a Laravel App to A Virtual Machine Using ansible Playbook

## Prerequisite
1. A Remote Virtual Machine( I used one from Linode)
2. A Non-root user
3. Ansible
4. Python3
5. A valid domain name (I used namesilo)

### Getting Started
- Clone this repository using git
- Edit the host file and add your non-root user to the `ansible_ssh_user=<name-of-non-root-user>`
- Edit the `vars.yml` and replace the domain value with your domain name
- To run the playbook, Run the following command:

> ansible-playbook -i hosts main.yml --ask-become-pass

- Pass in the password of your non-root user and allow the playboook to run




