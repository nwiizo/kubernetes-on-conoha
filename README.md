# kubernetes-on-conoha
Ansible playbook to create a Conoha(Openstack VM)  deploy kubernetes onto it


```
$ansible-playbook --version
ansible-playbook 2.6.3
```

```
ansible-playbook -i ./hosts.yml ./site.yml -l "<IP address>" -k
```


### to do
Install k8s on a server that can login with ssh

