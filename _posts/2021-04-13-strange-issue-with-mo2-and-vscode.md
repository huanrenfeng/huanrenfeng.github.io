---
title: "Strange Issue with MO2 and VSCode"
date: 2021-04-13
tags: [issue]
---


# Strange Issue with MO2 and VSCode

If vscode is using the system installation package, that is, if it is installed in Program Files, if you run VSCode with MO2, you will not be able to open Powershell inside, resulting in one-click compilation.

The terminal process "C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe" failed to launch (exit code: 3221225794).

The solution is to uninstall and re-use the User installation package

However, after running again after many days, I found that the error occurred again, which is strange

Restarting can’t solve it, and reinstalling can’t solve it. I found that changing powershell to cmd can’t solve it, and reinstalling the system installation package doesn’t work.

Is it an automatic update's fault? Downloaded version 1.51 in October 2020, still not working

After analysis, it should be a problem with VSCode, because MO2 can run cmd directly without any problems, but it will not work after VSCode

Another problem is also found, that is, if VSCode has not been opened through MO2 before, and then open a file through Explorer++, the file will be shown blank

It has been confirmed that it has nothing to do with administrator rights

After further observation, it cannot run successfully with any exe program that is configured to the shell path.

This should be a problem caused by MO2 and VSCode together. it's a pain in my ass.

Can't find a solution, so I had to use notepad++ for now 
