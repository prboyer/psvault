# PowerShell Vault

A Refined Collection of PowerShell Scripts

<p align="center">
    <img src="ps_vault.svg" alt="Logo for PSVault. Attribution to SVG Repo https://www.svgrepo.com/svg/217127/vault" width="400" height="400">
</p>


# [PSVault-Documentation Module](Documentation/README.md)
## Description
PowerShell files created to assist with automating the generation of documentation for other modules.

## PSVault-Documentation Cmdlets
### [Compile-ModuleDocs](Documentation/Docs/Compile-ModuleDocs.md)
Script that updates the README file on the front page.

### [Export-ModuleDocs](Documentation/Docs/Export-ModuleDocs.md)
Script used for generating Markdown documentation for PowerShell files.

# [PSVault-Utilities Module](Utilities/README.md)
## Description
A collection of PowerShell scripts that don't fit into a specific category.
## PSVault-Utilities Cmdlets
### [Apply-CodeSignature](Utilities/Docs/Apply-CodeSignature.md)
Script to automate signing of other scripts with digital certificate
### [Compare-FileHash](Utilities/Docs/Compare-FileHash.md)
Quick script to compare file hashes of contents between two directories
### [Copy-LocalUserProfile](Utilities/Docs/Copy-LocalUserProfile.md)
A custom cmdlet for quickly copying the contents of a user's profile to another location using ROBOCOPY.
### [Import-FromFile](Utilities/Docs/Import-FromFile.md)
Script to standardize importing lists from files.
### [Query-Users](Utilities/Docs/Query-Users.md)
PowerShell implementation of quser.exe

# [PSVault-Windows10 Module](Windows10/README.md)
## Description
A Collection of Windows 10 related PowerShell scripts for automation and simplification of administrative tasks.

## PSVault-Windows10 Cmdlets
### [Enable-InternetExplorer](Windows10/Docs/Enable-InternetExplorer.md)
Short script to add back Internet Explorer after it is not longer functioning.

### [Enable-Win10Feature](Windows10/Docs/Enable-Win10Feature.md)
Script to re-enable Windows 10 features that were removed due to / resulting from image capture issues.

### [Enable-WindowsPhotoViewer](Windows10/Docs/Enable-WindowsPhotoViewer.md)
A simple script to re-enable the legacy Windows Photo Viewer

### [Get-TLSVersion](Windows10/Docs/Get-TLSVersion.md)
Short script that returns the current TLS version settings

### [Remove-QuickAssist](Windows10/Docs/Remove-QuickAssist.md)
Simple function wrapper for removing Windows QuickAssist

### [Remove-UpdateAssistant](Windows10/Docs/Remove-UpdateAssistant.md)
Script to remove the Windows 10 Upgrade Assistant

### [Remove-Windows10Apps](Windows10/Docs/Remove-Windows10Apps.md)
Script for removing Windows 10 metro apps.

### [Repair-OneDrive](Windows10/Docs/Repair-OneDrive.md)
Script to repair Microsoft OneDrive if it is no longer working properly.

### [Repair-Windows10](Windows10/Docs/Repair-Windows10.md)
Script of repair tools and their appropriate parameters for diagnosing Windows 10 issues

### [Set-SystemInformation](Windows10/Docs/Set-SystemInformation.md)
Script to update the manufacturer information from the System Control Panel page

### [Set-TLSVersion](Windows10/Docs/Set-TLSVersion.md)
Short script to set the Security Protocol

### [Update-Windows10](Windows10/Docs/Update-Windows10.md)
Script that facilitates an online (running OS) upgrade of Windows 10 given a setup file from an expanded ISO


