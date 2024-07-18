---
layout: default
title: Extend WinRE with a PowerShell Script
nav_exclude: false
parent: Factoids
has_children: false
search_exclude: false
last_modified_date: 2024-02-25
---
# Extend WinRE with a PowerShell Script
To extend WinRE run the following script in an Admin PowerShell.Do this easily by pasting in just the one liner below.

```powershell
iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/r-Techsupport/rTS_Wiki/master/_includes/scripts/Extend-WinRE.ps1'))
```

The script being executed can be seen below, it is from the [official Microsoft article](https://learn.microsoft.com/en-us/windows-hardware/manufacture/desktop/add-update-to-winre?view=windows-11) for resolving this issue.

```
{% include scripts/Extend-WinRE.ps1 %}
```