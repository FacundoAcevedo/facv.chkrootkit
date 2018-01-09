chkrootkit
=========

Installs chkrootkit and set up cron to run it weekly.


Role Variables
--------------
* email_address: if something bad is found, sends an email to this remitent.

Dependencies
------------

None

Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: facv.chkrootkit, email_address: margaret@localhost }

License
-------

GPLv3

Author Information
------------------

Patches are wellcome
