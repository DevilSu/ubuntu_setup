# mount disk on startup

Reference: https://www.binarytides.com/ubuntu-automatically-mount-partition-startup/

# In terminal:

1. `sudo fdisk -l` or `lsblk`, find the /dev/sd? of the disk
2. `sudo blkid`, get UUID of the disk
3. `sudo cp /etc/fstab /etc/fstab.old`, backup the old one
3. `sudo gedit /etc/fstab`, add the line, make sure the path, file system type and UUID are correct.

	UUID=????? /media/???               ext4    exec,rw,errors=remount-ro,auto,user 0       0

	The order of exec,rw,... does matter. I can't ./a.out after gcc on NTFS if exec i not at front
