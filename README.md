## WIN-HYPER-V-CREATEVM
Powershell script that will create and configure a Hyper-V VM and start ISO. Built for automated deployment of a development VM.

### Allow unsigned scripts.
`set-executionpolicy remotesigned`

### Enable Hyper-V.
`Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All`

### Run Script via VSCODE, Powershell ISE, etc...

[CreateVM.ps1](
https://github.com/brettjrea/Windows-Hyper-V-BuildVM/blob/master/CreateVM.ps1)
