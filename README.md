## WIN-HYPER-V-CREATEVM
Powershell script that will create and configure a Hyper-V VM and start ISO. Built for automated deployment of a development VM.

### Allow unsigned scripts.
`set-executionpolicy remotesigned`

### Enable Hyper-V.
`Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All`

### Run Script via VSCODE, Powershell ISE, etc...

