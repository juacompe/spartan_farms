spartan_farms
=============

Vagrant configuration for Spartan course

Create new VM
-------------
For example, if you want to create a new virtual machine name `sheep1`

```
./create_new_instance sheep1
```

This will create a new machine in folder `sheep1`.

Connect to new VM
-----------------

```
cd sheep1
vagrant ssh
```

To shutdown the VM
------------------
At `sheep1` folder, run 

```
vagrant halt
```



To destory the VM
-----------------
At `sheep1` folder, run 

```
vagrant destroy
```

