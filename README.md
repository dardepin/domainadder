## Introduction
For GIT (Github) testing only! Ansible playbooks for Astra linux setup: first and second stages and adding to domain.
## Current Releases
0.1 - Initial Commit <br />
0.2 - New playboooks: ubuntu setup, updating wine and chrome, configuring apt sources.list and proxy exeptions<br />
## Platforms
Any Linux. With installed Ansible. Reboot module required Ansible version '2.7'. Required secret files generator (https://github.com/dardepin/gensecrets) and var in vars dir.
### Usage
Typical usage: ansible-playbook -i domainadder.yml --ask-vault-pass. See using notices in playbooks
## Licenses
Use and modify on your own risk.
