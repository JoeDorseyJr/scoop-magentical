# scoop-magentical

Scoop bucket for [Magentical](https://github.com/JoeDorseyJr/magentical) — Windows daemon distribution.

## Install

```powershell
scoop bucket add magentical https://github.com/JoeDorseyJr/scoop-magentical
scoop install magentical-server
```

Then register the Windows Service:

```powershell
powershell -ExecutionPolicy Bypass -File "$env:USERPROFILE\scoop\apps\magentical-server\current\install-server-windows.ps1"
```

## Update

```powershell
scoop update magentical-server
```

## Uninstall

```powershell
nssm stop MagenticalServer
nssm remove MagenticalServer confirm
scoop uninstall magentical-server
```
