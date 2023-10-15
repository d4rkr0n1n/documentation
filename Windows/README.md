# Windows

## Software Installations

### Open _Administrative Powershell_

- Press: `Win + R`
- Type: `powershell`
- Press: `Ctrl + Shift + Enter`

### Install _Chocolatey_

Execute:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

## Softwares

### List

- [VirtualBox](README.md#virtualbox)
- [Wget](README.md#wget)

### Installation

#### VirtualBox

##### With Extension

```powershell
choco install virtualbox -y --force --param "/ExtensionPack"
```

##### Without Extension

```powershell
choco install virtualbox -y --force
```

#### Wget

```powershell
choco install wget -y
```
