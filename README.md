# Miscellaneous_notes
PS C:\Users\a19758111> Find-Module PnP.PowerShell
Find-Package: No match was found for the specified search criteria and module name 'PnP.PowerShell'. Try Get-PSRepository to see all available registered module repositories.
PS C:\Users\a19758111> Get-Module PowerShellGet -ListAvailable

    Directory: C:\program files\windowsapps\microsoft.powershell_7.6.3.0_x64__8wekyb3d8bbwe\Modules

ModuleType Version    PreRelease Name                                PSEdition ExportedCommands
---------- -------    ---------- ----                                --------- ----------------
Script     2.2.5                 PowerShellGet                       Desk      {Find-Command, Find-DSCResource, Find-Module, Find-RoleCapability…}

    Directory: C:\Program Files\WindowsPowerShell\Modules

ModuleType Version    PreRelease Name                                PSEdition ExportedCommands
---------- -------    ---------- ----                                --------- ----------------
Script     1.0.0.1               PowerShellGet                       Desk      {Install-Module, Find-Module, Save-Module, Update-Module…}

PS C:\Users\a19758111> Get-Module Microsoft.PowerShell.PSResourceGet -ListAvailable

    Directory: C:\program files\windowsapps\microsoft.powershell_7.6.3.0_x64__8wekyb3d8bbwe\Modules

ModuleType Version    PreRelease Name                                PSEdition ExportedCommands
---------- -------    ---------- ----                                --------- ----------------
Binary     1.2.0                 Microsoft.PowerShell.PSResourceGet  Core,Desk {Compress-PSResource, Find-PSResource, Get-InstalledPSResource, Get-PSResourceRepository…}

Install-PSResource PnP.PowerShell               

Untrusted repository
You are installing the modules from an untrusted repository. If you trust this repository, change its Trusted value by running the Set-PSResourceRepository cmdlet. Are you sure you 
want to install the PSResource from 'PSGallery'?
[Y] Yes  [A] Yes to All  [N] No  [L] No to All  [S] Suspend  [?] Help (default is "N"): A
Install-PSResource: 'The proxy tunnel request to proxy 'http://he2a0012.emea2.cds.t-internal.com:8080/' failed with status code '407'."' Request sent: 'https://www.powershellgallery.com/api/v2/FindPackagesById()?%24filter=Id+eq+%27PnP.PowerShell%27+and+IsLatestVersion+eq+true&%24inlinecount=allpages&id=%27PnP.PowerShell%27'
Install-PSResource: Package(s) 'PnP.PowerShell' could not be installed from repository 'PSGallery'.
