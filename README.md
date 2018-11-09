# sog-ansible

## Setup

### Install required third-party roles
```
ansible-galaxy install -r requirements.yml
```


## Usage

### Syntax check
```
ansible-playbook --syntax-check -i inventory.yml site.yml
```

### Dry-run
```
ansible-playbook -C -i inventory.yml site.yml
```

### Deploy
```
ansible-playbook -i inventory.yml site.yml --ask-vault-pass
```

After starting you will need to enter the vault password, so ansible can decrypt the credentials. It is made available privately.
