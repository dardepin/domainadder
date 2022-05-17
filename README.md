## Introduction
For GIT (Github) testing only! Ansible playbooks for Astra linux setup: first and second stages and adding to domain.
## Current Releases
0.1 - Initial Commit <br />
0.2 - Repos changed to Yandex <br />
0.3 - Tools for updating chrome and mis added. Software versions are in group_vars directory <br />
0.4 - Playbook for Ubuntu hosts <br />
## Platforms
Any Linux. With installed Ansible. Reboot module required Ansible version '2.7'. Required secret files generator (https://github.com/dardepin/gensecrets) and var in vars/astra.yml
### Usage
Typical usage: ansible-playbook -i domainadder.yml --ask-vault-pass. See using notices in playbooks
## Licenses
Use and modify on your own risk.
