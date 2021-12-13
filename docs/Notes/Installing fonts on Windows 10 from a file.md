---
title: "Installing fonts on Windows 10 from a file"
tags:
  - "Computers/OperatingSystems/Windows10/Topics/Fonts"
  - "Computers/OperatingSystems/Windows10/PreinstalledApps/Settings"
date_created: 2021121011T1238
---
You can install [[OpenType]] and [[TrueType]] fonts for usage in [[Microsoft Word]] and other supported applications.

```mermaid
flowchart TB
	A[(Download font)] --> B{Is it in a `.zip` file? } -- Yes --> B1([Extract it]) --> B
	B -- No --> C[Drag it to the desktop]
	C --> D[Navigate to Start > Settings > Personalization > Fonts in Settings]
	D --> E[Click the rectangle in the upper right corner to collapse the menu]
	E --o E1[Make sure the file is visible on the desktop]
	E --> F[Drag the font file onto the marked area]
	F -.-> F1[Repeat as necessary] -.-> F
	F --> G[The font should appear in the Available Fonts list]
```

## Sources
