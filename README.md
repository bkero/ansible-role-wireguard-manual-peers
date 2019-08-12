Ansible Role for Wireguard Manual Peers
=========

This is an ansible role to set up and manage a Wireguard interface on a (series of) hosts, manually managing peer entries. This can be useful for organizations that separately manage some hosts.

Requirements
------------

This role should be applied against any Linux host running any of the supported distributions. Firewall access is necessary either through _iptables_ or an associated security group.

Role Variables
--------------

* _interface_: The name of the wireguard interface to be used on the hosts (default wg0)
* Hostvars (TODO)
** Public Key (TODO)
** Private Key (TODO)
** Peers (TODO)

Dependencies
------------

There are no additional dependencies needed to apply this role. This role only uses Ansible's built-in modules.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

Ben Kero <bkero@bke.ro>
