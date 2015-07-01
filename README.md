README
------

This repository is meant to be just a simple reference containing some sort of [Vagrantfile](http://docs.vagrantup.com/v2/vagrantfile/) samples.

In order to get up and running you need both [Vagrant](http://docs.vagrantup.com/v2/installation/) and [VirtualBox](https://www.virtualbox.org/manual/ch01.html#intro-installing) installed.

Once you setup them, just dive into some sample directory and get your Vagrant running by means of the following command:
```
cd minimal
vagrant up
```

In order to use your brand new Vagrant, just get logged into using SSH:
```
vagrant ssh
```

Once you are done, shutdown your virtual machine:
```
vagrant halt
```

Or else, if you want to discard it:
```
vagrant destroy -f
```

Simple like this.
