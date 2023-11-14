# Playbook - Ansible 101 Certification | Jonathan Wilson

## Updated: Nov 14, 2023

The alta3research-ansiblecert01.yml playbook was created for the Alta3 Ansible 101 Certification

The Git Repo should be cloned into the ~/alta3research-ansible-cert folder of the user's home drive

A variable "dinner_time" can be set to "False" when executing the Playbook if it is not feeding time for the Astronauts; otherwise, Mangia Mangia!

A variable "fetch_git_info" can be set to "False" when executing the Playbook to disable the display of Git Repo details

Sample command for starving the Astronauts and caring less about Git Repo info: "ansible-playbook ~/alta3research-ansible-cert/alta3research-ansiblecert01.yml -e dinner_time=False -e fetch_git_info=False"
