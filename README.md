### workstation setup
Boring script to help provision new debian installs

```
ansible-playbook -K main.yaml
```

### gnome gnotes
Observe gnome settings changes in real time:
```
dconf watch /
```
Some things are easier to modify using gsettings, others dconf.