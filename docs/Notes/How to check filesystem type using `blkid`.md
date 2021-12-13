---
title: "How to check filesystem type using `df`"
tags:
  - "Computers/OperatingSystems/GNULinux/CommandLine"
  - "Computers/OperatingSystems/GNULinux/Topics/DiskManagement"
  - "Computers/OperatingSystems/GNULinux"
  - "Meta/NoteType/HowTo"
  - "Computers/OperatingSystems/GNULinux/Packages/util-linux/blkid"
---
# How to check filesystem type using `blkid`

You can check filesystem type by using the [[blkid]] command.

Running the following returns a list of partitions, their filesystems, and some other info:
```bash
$ blkid /dev/sda3
```

## Sources
[[kili.WaysDetermineFilesystem.2017]]