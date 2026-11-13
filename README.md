# scoop-magentical

Scoop bucket for [Magentical](https://github.com/JoeDorseyJr/magentical) — AI agent platform for developers.

📖 **[Full setup guide →](https://github.com/JoeDorseyJr/magentical/blob/master/ALPHA_SETUP.md)**

---

## Quick Install

```powershell
scoop bucket add magentical https://github.com/JoeDorseyJr/scoop-magentical
scoop install magentical-server
```

Then register as a Windows Service (you'll be prompted for your Cloudflare Access credentials):

```powershell
powershell -ExecutionPolicy Bypass -File "$env:USERPROFILE\scoop\apps\magentical-server\current\install-server-windows.ps1"
```

The server starts automatically at login and appears in your notification area.

---

## Android App

Download the latest APK from the [Releases page](https://github.com/JoeDorseyJr/magentical/releases/latest) and sideload it on your Android device.

---

## Update

```powershell
scoop update magentical-server
```

---

## Uninstall

```powershell
nssm stop MagenticalServer
nssm remove MagenticalServer confirm
scoop uninstall magentical-server
```

---

## Need Help?

See the [full setup guide](https://github.com/JoeDorseyJr/magentical/blob/master/ALPHA_SETUP.md) for prerequisites, troubleshooting, and pairing instructions.
