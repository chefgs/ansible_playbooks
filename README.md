# ansible_playbooks

## Playbook functionality details
### Playbook : cloud_init_playbook
Below configurations are set when running the Playbook 
- Set a hostname on operating system level 
- Install a package called “my-monitoring-agent”. Assume that the package repository is already configured 
- Set the hostname in the configuration of the monitoring agent. Config file located at “/etc/mon-agent/agent.conf” 
- Ensure that the two users, “mac” and “bob” exists and are part of the group “my-staff” 
