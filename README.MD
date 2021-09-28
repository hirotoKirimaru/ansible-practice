# Ansibleの素振り

# インストール
```bash
pip install ansible
```

# シェルを実行する

```bash
ansible localhost -m shell -a 'hostname'
```

```bash
ansible localhost -i inventory -m ping -o
ansible sample -i inventory -m ping -o
ansible nodes -i inventory -m ping -o
ansible all -i inventory -m ping -o
```

# Playbook

```bash
ansible-playbook -i inventory playbook.yml 
ansible-playbook -i localhost error_message.yml 
```
