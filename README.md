To play test playbook run:
```
ansible-playbook -i environments/tests/inventory.ini test_playbook.yml -c local -Kk --extra-vars="ENV_HOST=local"
```