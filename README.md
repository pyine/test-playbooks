# test-playbooks

```bash
ansible-playbook --flush-cache --inventory example/env/cls_example/group_vars/test --limit testvaweb1 --extra-vars null --connection ssh example/debug.yml
```
