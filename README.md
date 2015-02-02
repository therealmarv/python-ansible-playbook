# python-ansible-playbook
Very basic example of how to run a command like `ansible-playbook` in Python itself.

Install:

```bash
virtualenv env
source env/bin/activate
pip install -r requirements.txt
```

Usage:

```bash
python deploy.py
```

It shows only a "Hello World!" message executed with Ansible on the local machine.  
It can be a good starting point for running an Ansible playbook locally.