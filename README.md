# format_bootable_usb_linux
 - `sudo fdisk -l` >> checking disk name 
 - `sudo umount /dev/sda1` >> a1 might be different on your terimibal 
 * format  
    - `sudo mkfs.ntfs /dev/sda1`
    - `sudo mkfs.vfat /dev/sda1`
    - `sudo mkfs.exfat /dev/sda1`
