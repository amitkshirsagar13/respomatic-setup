# respomatic-setup

### Mount Disk Drives:

```

sudo blkid
sudo apt-get install ntfs-3g
sudo vi /etc/fstab

/dev/sda1	/media/entertainment	vfat	rw,defaults	0	0
/dev/sdb1	/media/data	vfat	rw,defaults	0	0
```