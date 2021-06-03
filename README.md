# format_bootable_usb_linux
 - `sudo fdisk -l` # checking disk name 
 - or df 
 - 
 - `sudo umount /dev/sda1` # a1 ,might be different on your teriminal 
 * format  
    - `sudo mkfs.ntfs /dev/sda1`   # ntfs format type
    - `sudo mkfs.vfat /dev/sda1`   # vfat format type
    - `sudo mkfs.exfat /dev/sda1`  # exfat format type
   -
  * sudo fsck /dev/sdb1 verify usb
  
