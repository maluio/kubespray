# Kubespray Lab

Running k8s experiments on a cluster provisioned by kubespray


## Run playbook

```shell
venv/bin/ansible-playbook -i inventory/mycluster/hosts.yaml  --become --become-user=root cluster.yml
```
