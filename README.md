Ansible Playbook MacOS Prepare
=

The playbook do the following:

- Updates sudoers to allow admin group run any command with NOPASSWD property. It uses `roles-galaxy\common` role. To override defaut variables use `host_vars\localhost.yml`.

# How to Use

Once repository was cloned install dependencies. You need to run this command only the first time.

```
ansible-galaxy install -r requirements.yml -p ./roles-galaxy -f
```

Run playbook

```
ansible-playbook site.yml
```
