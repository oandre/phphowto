Step By Step Installing Symfony With Vagrant
############

1. Vagrant needs a Virtual Box. Download the virtual box for your OS in the following link: https://www.virtualbox.org/wiki/Downloads and install

2. After download the virtual box, download the Vagrant: http://downloads.vagrantup.com/ (latest version) and install it

3. After download and install the virtual box and vagrant, open this link: http://www.vagrantbox.es/ . The link show a list of Vagrant Boxes, pre-configured with some OS. In this case we will use CentOS 5.6 32bits.

4. In your terminal run this command:

```
vagrant box add centos32 http://yum.mnxsolutions.com/vagrant/centos_56_32.box
```

With this code you will create a Vagrant box, named centos32.