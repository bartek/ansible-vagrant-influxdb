# Ansible Vagrant profile for InfluxDB Server

This Vagrant profile installs [InfluxDB](https://influxdb.com/) using the
[Ansible](https://ansible.com) provisioner

## Getting Started

To use the Vagrant file, you will need to have done the following:

1. Download and Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
2. Download and Install [Vagrant](https://www.vagrantup.com/downloads.html)
3. Download and Install [Ansible](http://docs.ansible.com/intro_installation.html)

Then, in terminal:

    cd ./ansible-vagrant-influxdb
    ansible-galaxy install -r requirements.yml

Then, simply type:

    vagrant up

... And Vagrant will create the new VM, provisioned by Ansible.

You can now access InfluxDB via the provisioned ip address of the Vagrant VM
using the default ports.
