# Zephyr Dev

This project is meant to get all of the [Zephyr](https://www.zephyrproject.org) development tools setup inside a virtual machine for ease of development.

I mostly use it for Zephyr development on OSX without having to set up a case sensitive file system. It also helps set up a working development environment on a new machine in minutes.

## Installation

### Requirements

* VirtualBox (https://www.virtualbox.org/wiki/Downloads)
* vagrant (brew install vagrant)
* ansible (brew install ansible)

### Setup Instructions

1. Install VirtualBox, vagrant, and ansible
1. Clone this repo
1. Run `vagrant up`
	* This will setup an ubuntu VM with the Zephyr SDK and requirements
1. `vagrant ssh`

### Building test_app.

See the Zephyr [Application Development Primer](https://www.zephyrproject.org/doc/application/application.html) for more info

1. (Inside vagrant VM) `cd /vagrant/test_app`
1. To build project `make`
1. To run inside QEMU `make qemu`
