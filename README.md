## hid-sony
Kernel module for sony playstation controllers customized for some third-party devices.

## Build the module
```
$ make
```

## Unload the (current) module
```
$ sudo rmmod hid_sony
```

## Load the (new) module
```
$ sudo insmod hid-sony.ko
```
