# Ansible Cisco NXOS OSPF Fabric Builder 

Ansible code to build and test a spine and leaf OSPF fabric on a Cisco NXOS based infrastructure.

## Resource Contents
* `./playbooks` - Contains the build and test playbooks.
* `ansible.cfg` - The ansible configuration.
* `hosts` - The inventory file, including the loopback ips and interface range variables.

## Installation
```
git clone git@bitbucket.org:PacketFlow/ansible-cisco-nxos-ospf-fabric-builder.git
```

## Usage
```
ansible-playbook playbooks/fabric_build.yml
ansible-playbook playbooks/fabric_test.yml
```

## Online Documentation
The relating tutorial for this repo can be found at https://www.packetflow.co.uk/how-to-build-a-spine-and-leaf-fabric-with-ansible/.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact
If you want to contact us you can reach PacketFlow at contact@packetflow.co.uk.

## License
[MIT](https://choosealicense.com/licenses/mit/)
