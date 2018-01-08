# ansible-etcd3

A role which installs and manages a clustered etcd 3.x on CentOS 7

## Requirements

* ansible 2.4

## Example

modify inventories, then

```
ansible-playbook -i inventories/dev/hosts deploy-etcd3.yml
```
