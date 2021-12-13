---
title: "How to check filesystem type using `fsck`"
tags:
  - "Computers/OperatingSystems/GNULinux/CommandLine"
  - "Computers/OperatingSystems/GNULinux/Topics/DiskManagement"
  - "Computers/OperatingSystems/GNULinux"
  - "Meta/NoteType/HowTo"
  - "Computers/OperatingSystems/GNULinux/Packages/util-linux/fsck"
---
# How to check filesystem type using `fsck`
You can check filesystem type by using the [[fsck]] command:

```bash
fsck -N /dev/sda3
# Where -N disables checking the filesystem for errors
```

## Sources
[[kili.WaysDetermineFilesystem.2017]]