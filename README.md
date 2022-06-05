This repo contains the solutions to the introduction to vagrant exercises in the alx software engineering program

# How to Set Up Vagrant on your personal computer

Download Virtual box from this [link](https://www.virtualbox.org/wiki/Downloads)

Install Virtual box

Download Vagrant from this [link](https://www.vagrantup.com/downloads)

Install Vagrant

Open the Terminal application:

Now you will execute command line in your Terminal (each of them start with $)

Add the Ubuntu 20.04 (Focal) image to your box list: 

$ vagrant box add ubuntu/focal64 

Warning: this step can take time

Create your first virtual machine:

$ vagrant init ubuntu/focal64 -> it will generate a Vagrantfile with base = "ubuntu/focal64" - you don’t have to execute this command line everyday, only once, to create a new virtual machine

$ vagrant up -> it will start your virtual machine

$ vagrant ssh -> now you are inside your virtual machine.

