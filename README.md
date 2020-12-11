# CloudBees CI on traditional platforms

This is a work in progress on how to deploy CloudBees Core on traditional platforms using Ansible

### 1. Setup your hosts in the hosts.ini file

### 2. Install CloudBees Core Operations Center
`ansible-playbook -i hosts.ini install-operations-centers.yml`

### 3. Install CloudBees Core Client Masters

`ansible-playbook -i hosts.ini install-client-masters.yml`


## To do
Add playbooks for the configuration of the instances

## Full documentation
https://docs.cloudbees.com/docs/cloudbees-ci/latest/traditional-install-guide/
