# ansible-configs

Steps:

- Create `ansible` user on the target

  - Needs sudo access

- Create ssh key on the host and copy to the target
- Add target to the inventory
- Run `ansible-playbook -u ansible playbooks/webservers.yml -kK`
