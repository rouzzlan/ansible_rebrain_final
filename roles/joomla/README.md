Joomla
=========

Downloading and applying the right permissions to joomla files

Requirements
------------

Supported OS: Ubuntu
Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the
role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

variables used:

- `joomla_version`: the version of joomla that you wish to install
- `joomla_installation_dir` the location where you want to extract files that are required for joomla to run

```yaml
joomla_version: 5.1.4
joomla_installation_dir: /var/www/sites/joomla
```

License
-------

BSD

Author Information
------------------

Rouslan Sokolov
