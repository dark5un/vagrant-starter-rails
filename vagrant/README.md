# Description

Configure a ubuntu vm for wordpress


## Included tools and utilities

* Git
* Vim
* Byobu

## Dependencies

* Berkshelf

## Usage

Update the variables under the Settings part of the Vagrantfile to customize your install:

VM related settings:

* `project` is the project name (lowercase and _ only)
* `ip` is the unique IP to be given to the VM (shouldn't collide)
* `port` is the port for vagrant port forwarding
* `gems` is the list of gems you want installed in your vm (for instance compass or coffee-script)

Wordpress related settings:

* `title` is the Title to give to your wordpress
* `description` is the Description to give to your wordpress
* `username` is the username for the first admin account (password will be 'qwe')
* `email` is the email for the first admin account
* `sites` is the list of the sites you want in a multisite install (if you don't want multisites, leave an empty array [])