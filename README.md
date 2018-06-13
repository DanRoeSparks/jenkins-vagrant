# Vagrant Jenkins Install

## Prerequisites

1. Ansible https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html
2. Virtualbox https://www.virtualbox.org/wiki/Downloads
3. Vagrant https://www.vagrantup.com/docs/installation/

## Running

From the root of this project, run `vagrant up`
After installation, Jenkins will be available at http://local-ip:8080, with a default user/pass of admin/admin.
To see how the local IP is set, see the Configuration section below.


## Configuration

You can change the local IP of the Jenkins installation by editing `vagrant-config.yml`
1. Set the `local_ip` value for the reserved IP range you want to use.
2. Set the `usethis` value to the configuration block you want to use (`one_nine_two`|`ten`|`one_seven_two`)


