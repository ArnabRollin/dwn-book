# Installation

There are multiple ways to install the `dwn` CLI tool. Choose any one of the methods below that best suit your needs.

## Pre-compiled binaries

Executable binaries are available for download on the [GitHub Releases page]. Download the binary for your platform (Windows, macOS, or Linux). Locate the binary and do the following:

### MacOS and Linux

```zsh
sudo mkdir -p /usr/local/bin # Enter your password if it asks for it.
sudo mv <path to executable> /usr/local/bin
dwn --help 
```

### Windows

(CMD)

```cmd
mkdir "C:\Program Files\Dawn"
move <path to executable> "C:\Program Files\Dawn\"
dwn.exe --help
```

(PowerShell)

```powershell
New-Item -ItemType Directory -Path "C:\Program Files\Dawn" -Force
Move-Item –Path <path to executable> -Destination "C:\Program Files\Dawn\"
& "dwn.exe" "--help"
```

[GitHub Releases page]: https://github.com/ArnabRollin/dwn/releases
