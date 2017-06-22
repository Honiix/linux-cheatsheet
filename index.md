# Linux Cheatsheet

## Disk utilities

### Display a list of disks and their partitions:

```Shell
lsblk
lsblk -f         // with filesystem
lsblk -o +MODEL  // display manufaturer name
```

### List mounted partitions:


```Shell
mount
```

### Drives mounted using Nautilus (GUI) location:


```
/run/user/<username>/gvfs
```

### How to mount an image done with dd or ddrescue: 

```Shell
mount -o loop monimage.img monpointdemontage
```

### Look at kernel logs:

```Shell
dmesg
```

### List first level of folder from current location:

```Shell
du -hxd 1 .
```

### Calculate size of a folder

```Shell
du -hs <dossier>
```

### List folders size interactively (Fedora, CentOs, RedHat):

```Shell
sudo [yum | dnf] install ncdu
ncdu .
```


## Benchmarks

Todo
