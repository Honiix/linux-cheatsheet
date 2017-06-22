# Linux Cheatsheet

## Disk utilities

### Display a list of disks and their partitions:

```
lsblk
lsblk -f         // with filesystem
lsblk -o +MODEL  // display manufaturer name
```

### List mounted partitions:


```
mount
```

### Drives mounted using Nautilus (GUI) location:


```
/run/user/<username>/gvfs
```

### How to mount an image done with dd or ddrescue: 

```
mount -o loop monimage.img monpointdemontage
```

### Look at kernel logs:

```
dmesg
```

### List first level of folder from current location:

```
du -hxd 1 .
```

### Calculate size of a folder

```
du -hs <dossier>
```

### List folders size interactively (Fedora, CentOs, RedHat):

```
sudo [yum | dnf] install ncdu
ncdu .
```


## Benchmarks

Todo
