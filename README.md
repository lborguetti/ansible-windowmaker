ansible.windowmaker
==

Install Window Maker, Docks and Wicd with Ansible

Tested with:

- Ubuntu 14.04
- Fedora 21

## First install Requirements

- Install [Ansible](http://www.ansible.com/)

## Running

        git clone https://github.com/lborguetti/ansible.windowmaker
        cd ansible.windowmaker
        ansible-playbook wmaker.yml -i production_hosts -K -u ${USER}
