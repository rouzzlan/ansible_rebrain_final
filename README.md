# Installation instructions

Install Joomla with Ansible

### <font color="red">Disclamer</font>

The passwords displayed here are just as an example, change the credentials to other values.

## Run Playbook

```shell
ansible-playbook install_joomla.yml -i inventory.yaml  -e "@ansible.vault" --ask-vault-pass
```

or if `DEV_PASSWD` is not set

```shell
DEV_PASSWD=yourPasswd ansible-playbook install_joomla.yml -i inventory.yaml  -e "@ansible.vault" --ask-vault-pass
```

Vault password: `rebrain`

## Post installation

After running the playbook, you can follow the following steps to access your newly deployed website.

### Site access

By default, the domain name is set to `yourdomain.com`.</br>
The site is accessible at `http://yourdomain.com`.</br>
If working locally edit the `/etc/hosts` and add following line

```text
SERVER_IP yourdomain.com
```