# Winget_auto
winget json file for installing packages

## Requirements
- Winget package manager

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

- 7zip
- PortSwigger.BurpSuite.Professional
- FoxitReader
- Git
- Microsoft.WindowsTerminal
- Mozilla.Firefox
- Insecure.Nmap
- Notepad++
- Microsoft.VisualStudio.2022.Community-Preview
- WinSCP
- VSCodium
- PuTTY
- Microsoft.VCRedist.2015+.x86
- WiresharkFoundation.Wireshark
- PowerShell V7
- Microsoft.VCRedist.2008.x86
- Microsoft.VCRedist.2015+.x64
