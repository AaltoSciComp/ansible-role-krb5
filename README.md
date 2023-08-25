Ansible-role-krb5
=========

Initialize krb5.conf and manage kinit for a server.


Role Variables
--------------

**krb5_packages**: list of packages to install

**krb5_allow_weak_crypto: true/false. Wether weka crypto should be allowed in krb5.conf

**krb5_renew_cron: true/false. Wether there should be cron-task to renew machine krb5-ticket automatically.

**krb5_realm**: string. Default realm

**intDomain**: string. Addition site domain prefix.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-krb5 }

License
-------

MIT

Author Information
------------------

Mikko Hakala
