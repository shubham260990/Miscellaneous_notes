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
