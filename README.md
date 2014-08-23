# CoreOS Vagrant Jenkins

This repo provides a template Vagrantfile to create a CoreOS cluster virtual machine using Virtualbox which
will spin up a Jenkins cluster.

It's heavily based on the coreos-vagrant repository from CoreOS.

## Setup

[See the setup instructions](https://github.com/coreos/coreos-vagrant/)

git clone https://github.com/bobtfish/coreos-jenkins/
cd coreos-jenkins
Edit the userdata in user-data to have a new etcd discovery key
```

