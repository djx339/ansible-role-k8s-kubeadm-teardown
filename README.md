Ansible Role: kubernetes teardown
=========

Teardown a kubernetes cluster.

Requirements
------------

- kubernetes `master` must be placed in `master` section in inventory file.
- kubernetes `node` must be placed in `nodes` section in inventory file.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

```yml
- hosts: all
  roles:
    - { role: djx339.k8s-kubeadm-teardown }
```

License
-------

BSD

Author Information
------------------

This role was created by [Daniel D](https://github.com/djx339).
