# Linux Cheatsheet

## Disk utilities

### Display a list of disks and their partitions:

```shell
lsblk
lsblk -f         // with filesystem
lsblk -o +MODEL  // display manufaturer name
```

### List mounted partitions:


```shell
mount
```

### Drives mounted using Nautilus (GUI) location:


```
/run/user/<username>/gvfs
```

### How to mount an image done with dd or ddrescue: 

```shell
mount -o loop monimage.img monpointdemontage
```

### Look at kernel logs:

```shell
dmesg
```

### List first level of folder from current location:

```shell
du -hxd 1 .
```

### Calculate size of a folder

```shell
du -hs <dossier>
```

### List folders size interactively (Fedora, CentOs, RedHat):

```shell
sudo [yum | dnf] install ncdu
ncdu .
```


## Benchmarks

Todo
