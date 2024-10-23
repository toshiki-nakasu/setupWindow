# README

`applist.yaml`で定義したアプリケーション起動情報を元にWindowsマルチデスクトップでアプリケーションを起動する

## Step

1. `cp applist.example.yaml applist.yaml`
1. `pwsh ./setupWindow.ps1`
1. windowsマルチデスクトップでアプリケーションが起動する

## Need

```powershell
Set-ExecutionPolicy RemoteSigned
Install-Module -Name VirtualDesktop
Install-Module powershell-yaml
```
