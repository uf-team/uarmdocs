# Windows uArm tools installation

This guide would help you install all the environment uArm Tools need in windows.

## Requirement

- Windows 7 or above
- Administrator privilege

## Online installation script
- Open Powershell
- Please input the command to change the Powershell executionpolicy `Set-ExecutionPolicy unrestricted`, Press "Y" to approve
- input this online script `iex ((New-Object System.Net.WebClient).DownloadString('http://download.ufactory.cc/tools/windows/install.ps1'))`

if your network quality doesn't well, it supports proxy.
please run this command before you execute the online script: `$env:chocolateyProxyLocation = 'http://192.168.31.152:8016'`

what is the script actually did?
- chocolatey, Software Management. Automated. [https://chocolatey.org/][db374d94]
- Python2, (installed by chocolatey), uArm tools is based on python environment
- pip, (installed by chocolatey), this python tool will help us to download uArm tools.
- pyuarm, uArm python library include all python environment

  [db374d94]: https://chocolatey.org/ "https://chocolatey.org/"
