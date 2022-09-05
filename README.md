# infrastructure-ansible-packages
Ansible installation packages used by the Infrastructure Team

# Building

Use the `build` script to automatically download and build the desired version of Ansible

Run it with:

`./build <version>`

For example:

`./build 2.13.3`

This will download, build an Ansible .tar.gz package that can be installed on any server to run Ansible locally

# Installation

To install a desired version:

`pip3 install --user ansible-<version>.tar.gz`

For example:

`pip3 install --user ansible-2.13.3.tar.gz`

