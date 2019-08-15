Installation
=============

For Ubuntu 18.04
----------------
* Need to symlink /bin/bash to /usr/bin/bash (The binary actually compiled for 19.04)
```
$ sudo apt-get install gcc g++ gfortran pkg-config
$ sudo dpkg -i kangdroidmpich_1.0-0.deb
$ sudo ln -s /bin/bash /usr/bin/bash
```

For Ubuntu 19.04
----------------
```
$ sudo apt-get install gcc g++ gfortran pkg-config
$ sudo dpkg -i kangdroidmpich_1.0-0.deb
```