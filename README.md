# bootmsg
A linux kernel driver.
The linux kernel log buffer is a ring buffer, it will not be find the early log after system running for a while.
bootmsg will creat a device node /proc/bootmsg to store kernel boot log.
