# Vagrant Istio Setup

The setup is based on the setup described in
[this kubernetes blog](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/).

Requirements are `vagrant`, `virtualbox` and `ansible`.

## Vagrant Commands

```
# start up box
vagrant up --provider=virtualbox

# ssh into master
vagrant ssh k8s-master

# ssh into nodes (node #n)
vagrant ssh node-n
```
