# Chocolatey

## Install link
>  Chocolatey install for Powershell

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

code
## List
> Arbeit Server

```
choco install 7zip adobereader chromium Firefox greenshot notepadplusplus  putty teamviewer.host -y
```

> Arbeit Testclients

```
choco install 7zip adobereader chromium Firefox greenshot notepadplusplus  putty putty.portable rufus teamviewer.host vlc -y
```
> Arbeit mein Rechner

```
choco install 7zip adobereader chromium Firefox greenshot jabra-direct keepass mattermost-desktop nextcloud-client notepadplusplus openvpn phonerlite putty putty.portable rufus teamviewer vlc vscode winmerge wsl-ubuntu-2004  WhatsApp Spotify -y
```

> Privat
```
choco install 7zip adobereader chromium Firefox greenshot notepadplusplus putty putty.portable rufus teamviewer vlc WhatsApp Spotify -y
```
