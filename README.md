Vcenter move list vms 
=========

This role allows to migrate vms to move from host and datastore

Requirements
------------

- Ansible 2.9+
- `community.vmware` collection

Role Variables
--------------


- `vms`: List of vms to be migrated
- `datacenter`: Name of the datacenter to target
- `cluster`: Name of the cluster
- `new_datastore`: Name of the new datastore
- `new_host`: Name of the new esxi host
