# Laniakea-Galaxy
These are playbooks useful to install and configure Galaxy (here I use a test version)  
The playbook can be executed with the command "ansible-playbook"     
The inventory is useful to change the Python interpreter (Python2.7) if needed.

playbook.yml: to install galaxy through indigo-dc.galaxycloud ansible role

playbook_tools.yml: to automatically install tools from a Tool Shed into Galaxy (indigo-dc.galaxycloud-tools ansible role)

playbook_refdata.yml: to automatically install reference data using the CernVM File System and the corresponding Galaxy configuration (indigo-dc.galaxycloud-refdata ansible role)

For more information on [Laniakea Ansible Roles](https://laniakea.readthedocs.io/en/latest/admin_documentation/ansible/ansible_roles.html)
For more information on [Galaxy Flavours](https://laniakea.readthedocs.io/en/latest/user_documentation/galaxy/galaxy_flavours.html)
