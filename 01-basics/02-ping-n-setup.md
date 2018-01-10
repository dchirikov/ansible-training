To check if host available

```
# ansible -i hosts -u root -m ping vm
```

To enumerate all variables defined for host

```
# ansible -i hosts -u root -m setup vm
```
