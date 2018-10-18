nethserver_esmith
=========

Role for manage Netserver's e-smith dbs, read the networks and configuration db and store the json representation into `nethserver_netwoks` and `nethserver_config` variables.

Example Playbook
----------------

You can use at role list level for read the instance dbs:

    - hosts: servers
      roles:
         - role: amygos.nethserver_esmith

Or you can import role in the tasks list:

    - import_role: amygos.nethserver_esmith

    - debug:
        var: nethserver_config

    - debug:
        var: nethserver_networks

License
-------

MIT
