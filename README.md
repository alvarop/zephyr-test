# Zephyr Dev

This project is meant to get all of the zephyr development tools setup inside a virtual machine for ease of development.

## Installation

### Requirements
* VirtualBox (https://www.virtualbox.org/wiki/Downloads)
* vagrant (brew install vagrant)
* ansible (brew install ansible)

### Instructions
1. Install VirtualBox, vagrant, and ansible
1. Clone this repo
1. Run `vagrant up`
	* This will setup an ubuntu VM with the Zephyr SDK and requirements
1. `vagrant ssh`