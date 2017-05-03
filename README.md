VSTS-Agent
==========

A role to install and configure the VSTS-agent (Microsoft Visual Studio Team Services Build and Release Agent) for RedHat Enterprise 7.2+

Requirements
------------

Python-pip is installed and used to install a new enough version of pexpect, as the version packaged in redhat isn't new enough. Also rh-git29 is installed from software-collections, as VSTS requires a newer version of git.

Role Variables
--------------

At a minimum, override the variables vsts_accountname and vsts_poolname, other variables are documented in the defaults/main.yml file.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: sigio.vsts-agent }

License
-------

MIT

Author Information
------------------

github: sigio
