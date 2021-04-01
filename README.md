# PostgreSQL Ansible Playbook
Ansible playbook to deploy PostgreSQL for Django application

## Usage

### Configure
Update 'hosts' inventory and create 'credentials.yml' (Copy credentials.yml.example).

### Run
        ansible-galaxy collection install community.postgresql
        ansible-playbook -K site.yml

#### Tested on
* Ubuntu 20.04
