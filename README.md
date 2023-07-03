# Budibase on Docker

Deploy Budibase on a Rocky linux docker machine.

## Getting Started

These instructions will get you up and running on your local machine for
development and testing purposes.

### Prerequisites

Install Virtualbox https://www.virtualbox.org/ 

Install Vagrant https://www.vagrantup.com/

Install git https://gitforwindows.org/

Clone the repository onto your local machine

```
git clone git@github.com:oboudry-mvp/docker-budibase.git
cd docker-budibase
```

Provision the virtual machine

```
vagrant up
```

Connect to the budibase server using URL http://192.168.33.10:10000

Once you're finished playing with the VM, you can either suspend it (can be restarted with `vagrant up`) or destroy it.

```
vagrant suspend
vagrant destroy
```

