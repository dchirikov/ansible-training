To check if host available

```
# ansible -i hosts -u root -m ping all
# ansible -i hosts -u root -m ping vm
```

To enumerate all variables defined for host

```
# ansible -i hosts -u root -m setup vm
```

Run single command
```
ansible -i ../hosts2 -u root -m file -a 'path=/tmp/test1, state=directory' vm
```
