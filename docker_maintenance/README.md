### Docker housekeeping

Remove all unused containers, networks, images (both dangling and unreferenced), and volumes. 

Ref: https://docs.docker.com/engine/reference/commandline/system_prune/

**Requires Python3**

Instructions:

1. Update `hosts` file

2. Run `ansible-playbook -i hosts -b playbook.yml

