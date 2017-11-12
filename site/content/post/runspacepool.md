---
title: "Runspacepool"
date: 2017-11-08T17:18:38-05:00
draft: false
---
# RunspacePool and Variables leak.

Using Powershell from C# can be sometimes tricky.

I'm using a runspacepool to do multithreading in Powershell from C# and if you add your script content directly to the Powershell instance, the variables are kept alive in the RunspacePool.  

A solution is that instead of adding the content, the content should go in a file and invoked directly as if it was from the shell. I'll update this with code later
