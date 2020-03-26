# NFS instructions for x86

## Requirements

* [Termux](https://play.google.com/store/apps/details?id=com.termux)

## Steps

* If You Already Cloned/Have nfs Folder, Then You Need To Remove It First
```
 su
 rm -rf ~/nfs
```

* Clone the repo (DO NOT FORK! and DO NOT CLONE TO ANOTHER NAME THAN nfs, OTHERWISE IT WILL DOESN'T WORK. kthx)
```
 git clone https://github.com/HafizZiq/NFS-x86 nfs && cd ~/nfs
 su
 chmod 0755 nfs && ./nfs
```

* Install/Update
```
 su
 installnfs
```

* Pro key (for pro user only)
```
 su
 nfskey
```

* Uninstall
```
 su
 uninstallnfs
```

These all command may need you on the same directory, nfs dir

Happy hacking!
