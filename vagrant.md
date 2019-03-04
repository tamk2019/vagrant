#Vagrant

Vagrant is virtual machine managment software.
It's used for automating service tasks, skript handling and so on....

#For whom?

Vagrant is desinged for Service Operators, DevOps engineers,
Desingers and for hobbyisties.

Most of all its easy to use, has lots of ready on boxes to choose
your own environment.

#Installing
---ubuntu -for other systems:

https://www.vagrantup.com/downloads.html


Vagrant needs VirtualBox so:
```bash
sudo apt install virtualbox
```
Installing Vagrant:
```bash
sudo apt install vagrant
```
#Project

Create project folder to your desired location,
```bash
mkdir /home/user/vagrant/my-first-vagrant-project/

cd /home/user/vagrant/my-first-vagrant-project/
```
Search for desired box you want to use:

https://app.vagrantup.com/boxes/search
```bash
vagrant init ubuntu/trusty64  // Your box name
vagrant up
```
Now your virtual environment should be ready, you can:
//log in your box with ssh:
```bash
vagrant ssh
```
//Halt/Destroy your machine:
```bash
vagrant halt
vagrant destroy
```

For more information:

https://www.vagrantup.com/docs/index.html
