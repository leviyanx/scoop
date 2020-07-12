If encount this issue [Can't install scoop #1464](https://github.com/lukesampson/scoop/issues/1464), you can run the script (`scoop-installer.ps1`) with powershell manually to install `scoop`.

issue detail:
```
Exception calling "DownloadString" with "1" argument(s): "The operation has timed out"

At line:1 char:1
iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
  + CategoryInfo          : NotSpecified: (:) [], MethodInvocationException
  + FullyQualifiedErrorId : WebException
```
