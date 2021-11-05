Vagrant_libvirt
=========

Simple role to install vagrant and the vargant-libvirt plugin.

Based on [andrewrothstein.vagrant](https://galaxy.ansible.com/diodonfrost/vagrant)

Other good candidates would probably be any from [ansible galaxy](https://galaxy.ansible.com/search?keywords=vagrant&order_by=-relevance&page=1&deprecated=false&type=role).

Why use the libvirt provider?
-----------------------------
If you are just getting into the virtualization/automation stack of tools,
you should probably not try to use libvirt with vagrant.
There is much more support for virtualbox. Almost all the documentation and
examples are written for virtualbox. I just like libvirt a little better because
I like virt-manager.

Requirements
------------

TODO: this

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

TODO: this

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

TODO: this

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

TODO: this

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

Just getting into the whole molecule, vagrant, ansible, virtualization world.