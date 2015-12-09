ansible-bareos
==============

Ansible deployment of Bareos open backup application

Deploys 1 director, 1 storage with local backup device and any number of clients. 
Full backup job for each client on deploy. Modify roles/bareos-dir/templates/bareos-dir.conf to change backup job definitions.
Change passwords in group_vars/all .

control bareos using bconsole utility
