---
title: "Upgrading all applications installed via Chocolatey"
tags:
  - "Computers/OperatingSystems/Windows10/CommandLine"
  - "Computers/OperatingSystems/MicrosoftWindows/Windows10/Software/Chocolatey/\
    cup"
  - "Computers/OperatingSystems/Windows10/Topics/SoftwareManagement"
date_created: "20211208T231622"
---
*See also: [[Chocolatey]]*

You can update all Chocolatey packages with a simple command (ran in an administrative command line instance) [^1] :
```cmd
cup all
```

If you want to skip the individual confirmation prompts for each upgrade:
```cmd
cup all -y
rem Where "-y" skips the individual confirmation prompts.
```
