### workstation setup
set of ansible-playbooks for setting up a new debian 11 (gnome) desktop environment

lots of stuff to add still

```
ansible-playbook install.yml --ask-become-pass
```

### gnome gnotes
Observe gnome settings changes in real time:
```
dconf watch /
```
Some things are easier to modify using gsettings, others dconf.