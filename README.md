# Winget_auto
winget json file for installing packages

## Disable uac
Because otherwise you keep getting popups asking for approval to install an app

```powershell
Set-ItemProperty -Path REGISTRY::HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System -Name ConsentPromptBehaviorAdmin -Value 0
```

### Useage
```powershell
winget import -i .\winget-export.json --accept-package-agreements
```

### Apps

"7zip.7zip"
"PortSwigger.BurpSuite.Professional"
"Foxit.FoxitReader"
"Git.Git"
"Microsoft.WindowsTerminal"
"Mozilla.Firefox"
"Insecure.Nmap"
"Notepad++.Notepad++"
"Microsoft.VisualStudio.2022.Community-Preview"
"WinSCP.WinSCP"
"VSCodium.VSCodium"
"PuTTY.PuTTY"
"Microsoft.VCRedist.2015+.x86"
"WiresharkFoundation.Wireshark"
"Microsoft.PowerShell"
"Microsoft.VCRedist.2008.x86"
"Microsoft.VCRedist.2015+.x64"
