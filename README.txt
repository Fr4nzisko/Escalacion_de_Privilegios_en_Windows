## Escalación de privilegios local


Esta es una herramienta que te ayudará a crear tu propio taller de escalada de privilegios
local en windows 10 Pro x64.


* **La herramienta se debe ejecutar con permisos de administrador en PowerShell


```text
PS> C:\Windows\System32>
Enable-WindowsOptionalFeature -Online -FeatureName "SMB1Protocol-Client" -All
```


```text
.\EscalacionPrivilegiosWindows.bat
```


* **Una vez terminado de ejecutar el script se debe reiniciar la máquina.

