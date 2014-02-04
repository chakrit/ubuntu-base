Ubuntu Base
========

Updates, upgrades and install commonly needed tools across ubuntu server installs and
setup common shell parameters such as prompts.

Requirements
------------

Tested on Ubuntu 12.04 LTS.

Role Variables
--------------

**base_hostname**: Base system hostname. Content of this variable will be written to the
system's `hostname` file.

**base_prompt_string**: Global default prompt string. Defaults to showing the hostname and
currently logged-on user.

Dependencies
------------

-

License
-------

BSD

Author Information
------------------

Chakrit Wichian <service@chakrit.net> (http://chakrit.net)
