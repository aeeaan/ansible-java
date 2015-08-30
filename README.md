correcthorse.java
=========

An ansible role fwor installing java

Role Variables
--------------

| Variable		| Default							| Notes				|
| :---			| :---								| :---				|
| java_version		| 1.8.0								| should match package name	|
| java_devel		| false								| installs base devel rpm	|

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: correcthorse.java }

Dependencies
------------

- correcthorse.common

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)
