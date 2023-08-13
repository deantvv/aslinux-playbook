```bash
git submodule init && git submodule update --remote
poetry install
poetry shell
ansible-galaxy install -r requirements.yml
ansible-playbook -i inventory --ask-become-pass main.yml
```
