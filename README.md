govc
=========

Install govc binary

Requirements
------------

- gunzip

Role Variables
--------------

To set the specific version of the binary to install
- govc\_version: "0.12.1"

Path to install the binary.  Can be used to install to user local path, or system wide path.
- govc\_path: /usr/bin

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: tompscanlan.govc, govc_path: ~/bin }

License
-------

Copyright VMware

Apache

Author Information
------------------

Tom Scanlan
tscanlan@vmware.com
tompscanlan@gmail.com
