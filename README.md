devgoatse
=========

(NSFW)

Linux Kernel module for creating /dev/goatse character device.

/dev/goatse creates a continue stream of the famous goatse JPG image.

This device could be very useful for securely erase disks, in order to troll people looking for data on the disk.

You can use it in a very simple way:

    dd if=/dev/goatse of=/dev/disk-to-erase

    
Dependencies
=======

In order to compile the kernel module you should have the latest version of your Linux kernel headers.

On Ubuntu/Debian you can install them using:

    sudo apt-get install linux-headers-$(uname -r)

Installation and use
=======

    make
    ./goatse_register.sh
