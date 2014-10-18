# server initializer for ansible

```bash
$ ansible-playbook -l servers-root -i hosts init.yml -e "username=ylqjk email=ylqjk@example.com ssh_port=22 key_path=~/.ssh/id_rsa.pub"
$ ansible-playbook -l rails-servers -i hosts init.yml -e "username=ylqjk email=ylqjk@example.com ssh_port=22 key_path=~/.ssh/id_rsa.pub"
```
