borgbackup
=========

Configures and installs server and client configurations of borgbackup.

Requirements
------------

Borgbackup provided by distro.
Cronie on Arch
OpenSSH
flock tool

Role Variables
--------------

borgbackup_backup_server: resolvable hostname or ip to configure clients
borgbackup_time_between_backups: time in seconds until a backup expires and how often the cron job runs


A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

GPL v3

Author Information
------------------

Yevgeniy Kuksenko
