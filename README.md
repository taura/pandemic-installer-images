pandemic installer images
=========================

This repository contains "ready-to-burn" images of pandemic master, made by pandemic-installer tool.  To use these images, you don't need pandemic-installer.

how to use
=========================

 1. download any of the images under images/ directory
 1. burn the image into USB stick.  On Linux, simply do something like:

```
dd master_usb_image_based_on_ubuntu_18_04_2_desktop_amd64 /dev/sdb
```

CAUTION: sdb should be replaced by the device name of the USB stick.

Check the device name by, for example, disk utility (GUI) of Linux.  If GUI is not available consider using fdisk

On Windows, there seems a dd-like program, such as <a href="https://blog.halpas.com/archives/1258"> dd for windows </a>

FILES
=========================

NOTE: there is currently only one. which one you use does not really matter (as long as it successfully brings up your machine). any master image can copy any disk image of the master.

images/
  master_usb_image_based_on_ubuntu_18_04_2_desktop_amd64 --- master USB image, made fro ubuntu-18.04.2-desktop-amd64