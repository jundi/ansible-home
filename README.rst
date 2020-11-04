Ansible playbook that sets up nice command line environment with neovim on Centos7/8.


Install on remote centos7 host without root permissions::

    ansible-playbook -i remotehost, centos7.yml

or on local centos7 host without with root permissions::

    ansible-playbook -i localhost, centos7.yml -c local -K

Install on remote centos8 host without root permissions::

    ansible-playbook -i remotehost, centos8.yml

or on local centos8 host without with root permissions::

    ansible-playbook -i localhost, centos8.yml -c local -K
