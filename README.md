# README

Create an inventory file and specify 'master-nodes', 'worker-nodes' hosts.

Ex:

```
[master-nodes]
3.67.194.143
[worker-nodes]
18.194.105.136
```

Run ansible-playbook command. Ex:

```
ansible-playbook install-playbook.yaml -i inventory --private-key ~/.ssh/cluster.pem -u ubuntu
```

