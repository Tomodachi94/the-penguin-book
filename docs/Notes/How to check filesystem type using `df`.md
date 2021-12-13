---
title: "How to check filesystem type using `df`"
tags:
  - "Computers/OperatingSystems/GNULinux/CommandLine"
  - "Computers/OperatingSystems/GNULinux/Topics/DiskManagement"
  - "Computers/OperatingSystems/GNULinux"
  - "Meta/NoteType/HowTo"
  - "Computers/OperatingSystems/GNULinux/Utilities/df"
---
# How to check filesystem type using `df`

You can check filesystem type by using the [[df]] command.

Running the following returns a list of disks and their filesystems:
```bash
$ df -Th
```

Optionally, you can use [[grep]] to filter the results:
```bash
df -Th | grep "^/dev"
```

## Sources
[[kili.WaysDetermineFilesystem.2017]]