# れどみ

必須コマンド:

```
export WINEPREFIX=~/.wine32 && export WINEARCH=win32
```

WinePrefixを指定し32bitでwineを起動

```
winetricks dotnet48
```

いつもの。.NET framework4.8をインストール

```
wine "C:\\windows\\Microsoft.NET\\Framework\\v4.0.30319\\MSBuild.exe" {{Project}}.csproj
```

ビルドコマンド

`C://Program Files/Reference Assemblies/Microsoft/Framework/.NETFramework/v4.8/`

にdotnet48のアセンブリがあるからVBから輸送してくれば参照関連は全部解決した
