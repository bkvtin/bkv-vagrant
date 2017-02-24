# DEV environment

# Vagrant
I use vagrant with provider virtual box, we could also use with other provider vmware

```sh
# install virtual box
$ sudo apt-get install virtualbox
```

```sh
# install vagrant
$ sudo apt-get install vagrant
```

```sh
# install Dynamic Kernel Module Support Framework
$ sudo apt-get install virtualbox-dkms
```

### Getting started 
* Get the image url from [#Vagrantbox dot es] [vagrant]
* Add the image
```sh
$ vagrant box add trusty64 https://cloud-images.ubuntu.com/vagrant/trusty/current/trusty-server-cloudimg-amd64-vagrant-disk1.box
$ vagrant init
```

### References
* [#Sysadmincasts dot com] [url]






[vagrant]: <http://www.vagrantbox.es/>
[url]: <https://sysadmincasts.com/episodes/45-learning-ansible-with-vagrant-part-2-4>
