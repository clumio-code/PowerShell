-------------
Prerequisites
-------------
You need both ‘PowerShell’ and 'powerCLI' installed

------------
Installation
------------
If vSphere uses self-signed certificates, execute the following: 
- Powershell.exe Set-PowerCLIConfiguration -InvalidCertificateAction Ignore -Scope User

From the working directory (replace role name and server name]:
- Add_vSphere_role.ps1 -Role "[role_name]" -Server "[vCenter Server Name or IP]"
