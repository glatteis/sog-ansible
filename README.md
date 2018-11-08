# sog-ansible

## Setup

### Install required third-party roles
```
ansible-galaxy install -r requirements.yml
```


## Usage

### Dry-run
```
ansible-playbook --syntax-check -i inventory.yml site.yml
```

### Dry-run
```
ansible-playbook -C -i inventory.yml site.yml
```

### Deploy
```
ansible-playbook -i inventory.yml site.yml
```
