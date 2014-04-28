# Analytics Demo Platform

A virtual appliance configuration.

## The Tech

The "glue code" libraries being used:

* [Git](http://git-scm.com/) for source controlling.
* [Vagrant](http://www.vagrantup.com/) for local system and cloud hosted virtual machine provisioning.
* [Puppet](http://puppetlabs.com/) for system setup and infrastructure automating.
* [Virtualbox](https://www.virtualbox.org/) for local system running.

### Requirements For Running VM Locally

In order to run a VM locally, you will need to have the following installed:

1) Install [Git](http://git-scm.com/downloads).

3) Clone the `analitics-demo-platform` repository:

    git clone https://github.com/mhelabs/analytics-demo-platform.git

4) Install [Vagrant](http://www.vagrantup.com/downloads.html).

5) Install [Virtualbox](https://www.virtualbox.org/wiki/Downloads).

### Requirements For Running VM on AWS

### Virtual Machine Packages
This is an out of box solution for a staging and testing setup is installed with the following applications and services:

* [CentOS 6.4](http://www.centos.org/)
* [Open JDK 1.7.0_55](http://openjdk.java.net/)
* [MongoDb 2.4](http://docs.mongodb.org/manual/release-notes/2.4/)