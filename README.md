Role Name
=========

This role automates the process of installing Yottadb or GT.M.

Requirements
------------

The install will only take place on 64 bit systems

Role Variables
--------------

instdir - The directory in which to install Yottadb or GT.M

[ Default - /usr/local/yottadb ]

force - Whether to force the install irrespective of whether the system is of the recommended type or not (See YottaDB documentation for more details) Enter Yes or No

[ Default - "No" ]

gtm - Whether to install GT.M instead of Yottadb or not (Yes or No)

[ Default - No ]

group - The group that owns the installation

[ Default - root ]

user - The user that owns the installation

[ Default - root ]

zlib - Whether to install the zlib library or not (Yes or No)

[ Default - No ]

zlib - Whether to install the posix library or not (Yes or No)

[ Default - No ]


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      role: yottadb
      instdir: /opt/yottadb
      ...

Further Information
-------------------

The YottaDB website:

https://yottadb.com/

License
-------

BSD

Author Information
------------------

Raman Sailopal
