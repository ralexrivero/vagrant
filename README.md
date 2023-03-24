# vagrant

- `vagrant init ubuntu/focal64` # create Vagrantfile
- `vagrant up` # start VM
- `vagrant ssh` # connect to VM

To start a VM from a Vagrantfile in a different directory `cd` into that directory and run `vagrant up` or `vagrant up path/to/Vagrantfile`.

- `vagrant status` # show VM status
- `vagrant reload` # restart VM
- `vagrant halt` # stop VM
- `vagrant destroy` # delete VM

- `vagrant box list` # list boxes
- `vagrant box add ubuntu/focal64` # add box
- `vagrant box remove ubuntu/focal64` # remove box
