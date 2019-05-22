Ansible playbook that sets up nice command line environment with neovim on Centos 7. Requires pip.


Install on remote host without root permissions::

    ansible-playbook -i remotehost, site.yml

or on local host without with root permissions::

    ansible-playbook -i localhost, site.yml -c local -K
