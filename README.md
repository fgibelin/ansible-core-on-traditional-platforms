# ansible-core-on-traditional-platforms

This is a work in progress on how to deploy CloudBees Core on traditional platforms using Ansible

Setup your hosts in the hosts.ini file

To install CloudBees Core Operations Center, run ansible-playbook -i hosts.ini install-oc.yml
To install CloudBees Core Client Masters, run ansible-playbook -i hosts.ini install-cm.yml
