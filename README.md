```bash
git submodule init && git submodule update --remote
poetry install && poetry shell
ansible-playbook -i inventory --ask-become-pass main.yml
```
