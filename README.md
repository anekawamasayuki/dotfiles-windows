# dotfiles-windows

## Installation

PowerShell を開いて実行

```powershell
Set-ExecutionPolicy -Scope Process Unrestricted
iex(new-object net.webclient).downloadstring('https://raw.githubusercontent.com/anekawamasayuki/dotfiles-windows/master/make.ps1')
```

## Initialize

```
code $env:USERPROFILE\.gitconfig.local
```

## 他、手動でやること

[Mac使いがWindows開発環境構築してみたログ - Qiita](https://qiita.com/hush_in/items/1ac22f4c4c07c7df7900)
