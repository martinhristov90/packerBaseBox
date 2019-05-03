# How to create a vagrant base box

# Purpose

This repository's sole purpose is to demonstrate how to built a Vagrant box with virtual box provider using Packer.

# Technologies in use :

- Packer
- Vagrant
- VirtualBox

# How to install the needed technologies :

- [How to install Packer](https://www.packer.io/intro/getting-started/install.html)
- [How to install Vagrant](https://www.vagrantup.com/docs/installation/)
- [How to install VirtualBox](https://www.virtualbox.org/manual/ch02.html)


# How to use

- Clone this git repository using `git clone https://github.com/martinhristov90/packerBaseBox.git`
- Switch into the directory of the project using : `cd packerBaseBox`
- Let Packer build the Vagrant box for you using : `packer build templete.json`
