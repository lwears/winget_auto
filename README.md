# winget_auto
winget json file for installing packages

## disable uac

```powershell
Set-ItemProperty -Path REGISTRY::HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System -Name ConsentPromptBehaviorAdmin -Value 0
```

### useage
```powershell
winget import -i .\winget-export.json --accept-package-agreements
```
