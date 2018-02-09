## Locks up on sleep and powerdown
[https://askubuntu.com/questions/764568/ubuntu-16-04-hangs-on-shutdown-restart/792086#792086]

Modify /etc/default/grub
```
GRUB_CMDLINE_LINUX_DEFAULT="quiet splash acpi=force"
```

