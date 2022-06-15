<h1 allign="center">MT6701U DRIVER FIX</h1>

### To Do

<p allign="center">

```sh
$ make -C /lib/modules/$(uname -r)/build M=$(pwd) modules
    # Remove device
$ sudo rmmod mt7601u
$ sudo insmod ./mt7601u.ko
    # Insert device
```


