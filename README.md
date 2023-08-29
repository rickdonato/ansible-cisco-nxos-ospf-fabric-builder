# Ansible Cisco NXOS OSPF Fabric Builder 

Ansible code to build and test a spine and leaf OSPF fabric on a Cisco NXOS based infrastructure.

## Contents of Repo
* `./playbooks` - Contains the build and test playbooks, along with the group vars.
* `ansible.cfg` - The ansible configuration.
* `hosts` - The inventory file, including the loopback ips and interface range variables.

## Installation
```
git@github.com:rickdonato/ansible-cisco-nxos-ospf-fabric-builder.git
```

## Usage
```
ansible-playbook playbooks/fabric_build.yml
ansible-playbook playbooks/fabric_test.yml
```

## Additional Documentation
The relating tutorial for this repo can be found at https://www.packetflow.co.uk/how-to-build-a-spine-and-leaf-fabric-with-ansible/.
