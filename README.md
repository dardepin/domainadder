## Introduction
For GIT (Github) testing only! Ansible playbooks for Astra and Ubuntu linux setup: first and second stages and adding to domain.
## Current Releases
0.1 - Initial Commit; <br />
0.2 - New playboooks: Ubuntu setup, updating Wine and Chrome, configuring apt _sources.list_ and proxy exeptions; <br />
0.3 - New playbook: Doctor Web install/renew, Vipnet firewall setup and updating old playbooks; <br />
0.3.1 - Kaspersky Endpoint Security installation playbook added. Dr Web will be deleted if detected;
## Platforms
Any Linux with installed Ansible. Reboot module required Ansible version '2.7'. Required [secret files generator](https://github.com/dardepin/gensecrets) and vars in `vars` dir.
## Usage
Typical usage:
> ansible-playbook -i domainadder.yml --ask-vault-pass.

See using notices in playbooks
## Licenses
Use and modify on your own risk.
