Role Name
=========



Requirements
------------

This collection uses the ansible-freeipa and rhel-system-roles packages from the RHEL 9 appstream repository
To run the Windows roles, you will need to install the python3-winrm package and the following Ansible module:
  ansible-galaxy collection install ansible.windows
If you are running older versions of Windows, 2016 and earlier, zou must also run the WinRM Memory Hotfix and WinRM Setup scripts on the Window server to allow WinRM to accept connections from Ansible.
The doc is here: https://docs.ansible.com/ansible/latest/os_guide/windows_setup.html


Role Variables
--------------

Variables are in two places: inventory and secret.yml
  inventory holds all public variables.


Author Information
------------------

Mike Ralph, Sr Technical Account Manager
