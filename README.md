# EthicalFun
Ethical, clean hacking pranks.

Creates an object "objShell" using the "CreateObject" function and assigns it the "WScript.Shell" object, which allows the script to interact with the Windows operating system.
It then creates a message box with the text "OPEN YOUR EYES"
Then it uses the objShell.Run method to execute the following commands in the order they are listed:

"cmd.exe /k ping google.com -t" which opens the command prompt and runs the command "ping google.com -t" which sends an endless stream of ping requests to the specified IP address or URL.
"taskmgr.exe" which opens the Task Manager in Windows.
"https://www.nexusmods.com/newvegas/users/2218631" which opens the specified website in default web browser.
"calc.exe" which opens the Calculator application in Windows.
"mspaint.exe" which opens the Microsoft Paint application in Windows.
