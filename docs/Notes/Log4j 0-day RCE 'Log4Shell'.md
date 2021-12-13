---
title: ""
tags:
  - "Computers/ProgrammingLanguages/Java/Libraries/log4j/Security"
  - "Computers/Security/Vulnerabilities/RemoteCodeExecution/Log4Shell"
date_created: 20211210101524
ref:
  - cve: "CVE-2021-44228"
---
A [[Zero-day vulnerability|zero-day vulnerability]] was discovered in the [[Java]] package [[Log4j (Java)|log4j]]. It allowed for [[Remote code execution attack|remote code execution]] on Java versions under `6u211`, `7u201`, `8u191`, and `11.0.1` and `log4j` versions under 2.15.0.[^1]

Multiple applications were affected, including [[iCloud]], [[Steam (gaming platform)|Steam]], and [[Minecraft]].

The problem can be temporarily migitated by adding the `-formatMsgNoLookups=true` flag to a vulnerable Java application.
[^1]: [[thompson.Log4ShellRCE0day.2021]]