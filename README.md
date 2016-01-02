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
$ vagrant box add trusty64 http://files.vagrantup.com/trusty64.box
$ vagrant init
```


[vagrant]: <http://www.vagrantbox.es/>
