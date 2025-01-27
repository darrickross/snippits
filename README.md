# Snippets

Small snippets which are helpful to keep

## Powershell

### WSL

<https://learn.microsoft.com/en-us/windows/wsl/install-manual>

```ps
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart

dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart

wsl.exe --install

wsl --set-default-version 2
```
