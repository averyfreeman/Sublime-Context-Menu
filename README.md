---
title: "Sublime Text Context Menu README.md"
author: avery
date: 2021-10-18
---

# Sublime Text
---
#### Add right-click context "open with..." option to Windows 10

original source: https://gist.github.com/jackielii/6869515

[//]: @ 2021-10-18

I tried another text editor which removed the "open with Sublime Text" option from my context menu and wanted it back.

I am running Sublime Text 4, so I wanted to make some additions to this and re-publish it for other people

This puts it right near the top, by options like "Open with VS Code" etc.

Note: You can verify the script worked by going to Computer\HKEY_CLASSES_ROOT\*\shell and looking for the key "Open with Sublime Text" - but you may have to restart your Windows Explorer after running it before the option shows up in your context menu. 

Tested with:
```
$ subl --version
Sublime Text Build 4113
```