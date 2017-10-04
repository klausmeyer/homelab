# Homelab

Ansible setup for my personal homelab setup.

```
$ ansible-galaxy install -r requirements.yml
$ ansible-playbook -i hosts site.yml
$ ansible -i hosts docker -a 'docker ps'
```
