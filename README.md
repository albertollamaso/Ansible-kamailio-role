Ansible's Kamailio role
=========================

This role is intendent to replicate the steps to compile kamailio from the git repository. 
You can find the original steps at https://www.kamailio.org/wiki/install/4.4.x/git

The intention is to have a kamailio role multi plattform.

I am sharing this role as a source of inspiration and feel free to suggest improvements and changes.

TODO 
------------

* Finish the playbook when OS is RedHat family
* Add RTPProxy as part of the compilation process
* Add a new variable for modules to compile in order to have it dynamic

Requirements
------------

* Ubuntu
* CentOS
* Ansible 2.0
* Python


Role Variables
--------------

The following four variables are used in the setup process and are described below:

- `kamailio_version` : This is the version of Kamailio to be download from Git
- `dest_directory` : The destination directory to be clone the kamailio's source code
- `git_clone` : Kamailio folder to be created when the clone process is performed
- `MySQL_root_pass` : MySQL password for root


License
-------

GPL V.2

Author Information
------------------

Author : Alberto LLamas

Email : albertollamaso@gmail.com
