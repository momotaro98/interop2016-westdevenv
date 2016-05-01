Building interop2016 developing environment stack and deploying Application using Ansible Playbooks.
-------------------------------------------

These playbooks require Ansible 1.2.

## Build dev environment with vagrant


The stack can be deployed using the following
command:

```
ansible-playbook -i hosts site.yml --sudo -k -vv
```
