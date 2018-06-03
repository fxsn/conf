My personal dotfiles/configuration files. Installation is rather clunky and expects certain requirements to be met to function.

install.yml contains a (very) simplified (and frankly quite awful) Ansible yaml file for installing the dotfiles.

Dotfiles is expected to be located at home folder.

```bash
ansible-playbook --ask-sudo-pass ~/dotfiles/install.yml
```
