[![MIT License](https://raw.githubusercontent.com/DO1JLR/ansible-webtv-playbook/main/.github/license.svg?sanitize=true)](https://github.com/DO1JLR/ansible-webtv-playbook/blob/main/LICENCE)

Ansible playbook to set up the rC3 Waffle WEBTV
=========================================

This is a ansible playbook to setup the rC3 Waffle WEB-TV... It is a work in progress and currently not redy to use...



 Tipps und Tricks:
---------
### git submodule
Dieses Ansible verwendet submodule. Vergesst nicht diese regelmäßig mit auszuchecken!
```
git config submodule.recurse true
git submodule update --init --recursive
```

### Standard Playbook
Das standard Playook ist ``site.yml``. Womöglich sind hier andere Playbooks eingebunden...

### best practise Ansible-Vault:
[docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.htm](https://docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.html#tip-for-variables-and-vaults)

### weitere Methide variablen ins ansible vault:
```
ansible-vault encrypt_string 'encrypted_secret_string_value' \
  -n string_name
```
