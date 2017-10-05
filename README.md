# Vagrant PHP7 
Standart Vagrantfile for KDS development

## Prerequisit 
- NFS Server
````
apt-get install nfs-kernel-server (ubuntu)
````

## What's inside?

- Ubuntu Xenial64
- Vim, Git, Curl, etc.
- Apache
- PHP7 with some extensions
- MySQL 5.6
- Redis
- Composer
- phpMyAdmin

## How to use

- Clone this repository into your project
- Run ``vagrant up``
- Add the following lines to your hosts file:
````
192.168.100.100 app.dev
192.168.100.100 phpmyadmin.dev
````
- Navigate to ``http://app.dev/`` 
- Navigate to ``http://phpmyadmin.dev/`` (both username and password are 'root')
