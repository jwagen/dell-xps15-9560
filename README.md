## Locks up on sleep and powerdown
[https://www.reddit.com/r/Dell/comments/63cavx/fixed_nvidia_1050_freezing_in_ubuntu_linux/]

Modify /etc/default/grub
```
GRUB_CMDLINE_LINUX_DEFAULT="quiet splash acpi_rev_override=1"
```

