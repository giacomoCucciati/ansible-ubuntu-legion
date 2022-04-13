## How to run ansible in local

```
https://www.middlewareinventory.com/blog/run-ansible-playbook-locally/#Method2_Using_local_action_clause_in_the_ansible_playbook
```

## Launch this playbook

 
```
ansible-playbook -i my_hosts install-just-vim.yml -K -C
with:
-C: dry run
-K: ask password
```

```
ansible-playbook -i my_hosts install-all.yml -K
with:
-C: dry run
-K: ask password
```
