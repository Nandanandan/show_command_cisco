# Execute show commands in CISCO IOS

_Inventory_

- Make an entry of hosts in `inventory/hosts` file.
- Make an entry for inventory path in ansible.cfg
- Categorize devices in the inventory as required.

_Test reachability_

```
ansible -m ping all
```

_Execute_the_playbook_

```
ansible-playbook -u <username> -k ansible/playbook.yml
```

