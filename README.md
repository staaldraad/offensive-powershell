# Offensive Powershell

Contains a collection of Powershell scripts that have come in handy on assessments. These were either written as a once off, or with the idea that they could be useful in general.

## Scripts

#### mini-rev.ps1
A reverse shell written in Powershell. Connects back to either a nc listener, or mini-rev-listener.ps1. Passes commands straight through to a subprocess.
Basic commands such as `ls` and `dir` will be run as Powershell commands.

#### mini-rev-listener.ps1
A handler for reverse shells, think of it as a BASIC nc in Powershell. Accepts connection and sends commands you type. `exit` should exit.
