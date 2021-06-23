# PowerShell Vault

A Refined Collection of PowerShell Scripts

            # PowerShell Vault

            A Refined Collection of PowerShell Scripts
            
            <p align="center">
                <img src="ps_vault.svg" alt="Logo for PSVault. Attribution to SVG Repo https://www.svgrepo.com/svg/217127/vault" width="400" height="400">
            </p>
            
            [![PSScriptAnalyzer](https://github.com/prboyer/PSVault/actions/workflows/powershell-analysis.yml/badge.svg?branch=prboyer-patch-1)](https://github.com/prboyer/PSVault/actions/workflows/powershell-analysis.yml)

# [PSVault-ActiveDirectory Module](ActiveDirectory/README.md)
## Description
A collection of Active Directory related PowerShell scripts.
## PSVault-ActiveDirectory Cmdlets
### [Copy-UserGroupMembership](ActiveDirectory/Docs/Copy-UserGroupMembership.md)
Copies security group memberships from one user to one or more users
### [Disable-Users](ActiveDirectory/Docs/Disable-Users.md)
Script to disable AD users without deleting their accounts
### [Get-ADUserDate](ActiveDirectory/Docs/Get-ADUserDate.md)
Script for determining when AD user accounts were created.
### [Get-ComputerData](ActiveDirectory/Docs/Get-ComputerData.md)
Cmdlet to quickly return information about a AD-joined computer
### [Get-ProfileSize](ActiveDirectory/Docs/Get-ProfileSize.md)
Script to calculate the size of a user profile on a profile server
Script that adds users to an AD Security group from a list of names (ln, fn mi) in text file
### [Migrate-UserProfile](ActiveDirectory/Docs/Migrate-UserProfile.md)
Script used in preparing to migrate from a Windows 7 to Windows 10 environment.
This copies the contents of a user's Windows 7 roaming profile to a new Windows 10 (V6) roaming profile on a specified profile server.

<hr>

# [PSVault-Adobe_CreativeCloud Module](Adobe_CreativeCloud/README.md)
## Description
PowerShell scripts for administrating Adobe Creative Cloud
## PSVault-Adobe_CreativeCloud Cmdlets
### [Enable-AppsPanel](Adobe_CreativeCloud/Docs/Enable-AppsPanel.md)
Quickly resolve the Adobe Creative Cloud Desktop app displaying a "You don't have access to manage apps" message

<hr>

# [PSVault-BitLocker Module](BitLocker/README.md)
## Description
Scripts for managing built-in Windows Disk Encryption (BitLocker)
## PSVault-BitLocker Cmdlets
### [Activate-BitLocker](BitLocker/Docs/Activate-BitLocker.md)
Script for manually activating BitLocker on Windows 10 machines
### [Get-BitlockerKey](BitLocker/Docs/Get-BitlockerKey.md)
Script that runs a report against your AD instance to query for escrowed Bitlocker recovery keys.

<hr>


# [PSVault-Documentation Module](Documentation/README.md)
## Description
PowerShell files created to assist with automating the generation of documentation for other modules.

## PSVault-Documentation Cmdlets
### [Compile-ModuleDocs](Documentation/Docs/Compile-ModuleDocs.md)
Script that updates the README file on the front page.

### [Export-ModuleDocs](Documentation/Docs/Export-ModuleDocs.md)
Script used for generating Markdown documentation for PowerShell files.


<hr>

# [PSVault-GroupPolicy Module](GroupPolicy/README.md)
## Description
A collection of PowerShell scripts needed to fully backup and document a enterprise Group Policy environment.
## PSVault-GroupPolicy Cmdlets
### [Check-GPPermissions](GroupPolicy/Docs/Check-GPPermissions.md)
Script to report GPOs in a domain that do not have accessible ACLs applied.
### [Get-GPLinks](GroupPolicy/Docs/Get-GPLinks.md)
Script to provide either a TXT or CSV report of linking relationships between OUs and GPOs.
### [Run-GPOBackup](GroupPolicy/Docs/Run-GPOBackup.md)
All-in-one GPO Backup Script.
It leverages external modules/functions to create a robust backup of Group Policies in a domain.

<hr>

# [PSVault-Office365 Module](Office365/README.md)
## Description
PowerShell scripts for managing and configuring Office365
## PSVault-Office365 Cmdlets
### [Get-O365ServicingChannel](Office365/Docs/Get-O365ServicingChannel.md)
Script to quickly determine what Office 365 servicing channel a PC is subscribed to
### [New-PPTFromFiles](Office365/Docs/New-PPTFromFiles.md)
Quickly create a PowerPoint presentation from a folder full of files (like screenshots)
### [Repair-O365Click2Run](Office365/Docs/Repair-O365Click2Run.md)
Script that calls the O365 ClickToRun executable with the appropriate parameters for a repair.
### [Set-O365ServicingChannel](Office365/Docs/Set-O365ServicingChannel.md)
A quick and handy script for modifying the Windows Registry to switch the Office 365 servicing channel.

<hr>

# [PSVault-SCCM_MECM Module](SCCM_MECM/README.md)
## Description
## PSVault-SCCM_MECM Cmdlets
### [Build-MECMComputerReport](SCCM_MECM/Docs/Build-MECMComputerReport.md)
Script that extracts computer information and user information from all assets in a given MECM collection
### [Remove-CMPrimaryUser](SCCM_MECM/Docs/Remove-CMPrimaryUser.md)
A script to remove user device affinity associations from devices in SCCM for a given user

<hr>

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

<hr>

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
### [Get-ComputerSpecs](Windows10/Docs/Get-ComputerSpecs.md)
A PowerShell script to create a report of a machine's hardware.
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

<hr>


