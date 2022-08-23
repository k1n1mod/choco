# Chocolatey

## Install link
>  Chocolatey install for Powershell
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

## List
> Arbeit Server
```
choco install 7zip adobereader chromium Firefox greenshot notepadplusplus  putty teamviewer.host --ignore.checksums -y
```

> Arbeit Testclients
```
choco install 7zip adobereader chromium Firefox greenshot notepadplusplus  putty putty.portable rufus teamviewer.host vlc --ignore.checksums -y
```

> Arbeit mein Rechner
```
choco install 7zip adobereader chromium Firefox greenshot jabra-direct keepass mattermost-desktop nextcloud-client notepadplusplus openvpn phonerlite putty putty.portable rufus teamviewer vlc vscode winmerge wsl-ubuntu-2004  WhatsApp Spotify --ignore.checksums -y
```

> Privat
```
choco install 7zip adobereader chromium Firefox greenshot notepadplusplus putty putty.portable rufus teamviewer vlc WhatsApp Spotify --ignore.checksums -y
```

> List all packages
```
clist -l
```

> Export a List of all packages
```
choco list -lo -r -y | % { "choco install " + $_.Replace("|", " -version ") + " -y" } > C:\temp\Install.ps1
```
