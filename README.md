# Powershell
PoweShell is a modern command shell that includes the best feature of other popular shell. This shell incldues the following features:
1. Robust command line history 
2. Tab completion and command predictions.
3. Supports commands and parameter alieases 
4. Pipeline for chaining command. 
5. In console help system, similar to UNIX man page. 

PowerShell command (cmdlet)
=

Commands for powershell are known as cmdlets (command lets), Powershell allows you to run any command avaialble on your system. 

Cmdlet name
= 
Powershell uses ```Verb-Noun``` name pair to name cmdle. For example ```Get-command``` cmdlet included in powerShell is used to get all the cmdlet that are registered in the command shell. The ver identify the action that the cmdlet performs, and the noun identifies the resource on which the cmdlet pefroms it's action. 

cmdlet
=
```Get-command```

The Get-command cmdlet gets all the commands that are installed on the computer, including cmdlet , allies, functions, filters, script, and applications. 

```Get-command -noun Service```


