# Inventories 

```shell
ansible all -m ping -o

ansible ubuntu -m ping -o

ansible centos -m ping -o

# execute id command in remote server
ansible all -m command -a 'id' -o



``` 