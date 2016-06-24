# PowerShell
Collection of useful PowerShell modules, scripts, snippets and templates

## Description

Automate all the things

## Module

### LazyAdmin

Download the folder [Module/LazyAdmin](Module/LazyAdmin) and save it under `C:\Users\%username%\Documents\WindowsPowerShell\Modules`. Then run the command `Import-Module LazyAdmin`

Available Functions:

* [Convert-Subnetmask](Module/LazyAdmin/Convert-Subnetmask.ps1) - Convert a subnetmask to CIDR and vise versa ([view documentation](Documentation/Convert-Subnetmask.README.md)) 
* [Get-InstalledSoftware](Module/LazyAdmin/Get-InstalledSoftware.ps1) - Get all installed software with DisplayName, Publisher and UninstallString ([view documentation](Documentation/Get-InstalledSoftware.README.md))
* [Get-WindowsProductKey](Module/LazyAdmin/Get-WindowsProductKey.ps1) - Get the Windows product key and some informations about the system ([view documentation](Documentation/Get-WindowsProductKey.README.md))
* [Get-WLANProfile](Module/LazyAdmin/Get-WLANProfile.ps1) - Get all WLAN-Profiles on your **local system**, include password ([view documentation](Documentation/Get-WLANProfile.README.md))
* [New-IPv4Subnet](Module/LazyAdmin/New-IPv4Subnet.ps1) - Calculate a subnet based on an IP-Address within the subnet and the subnetmask/CIDR ([view documentation](Documentation/New-IPv4Subnet.README.md))
* [New-RandomPassword](Module/LazyAdmin/New-RandomPassword.ps1) - Generate a random password with a freely definable number of chracters ([view documentation](Documentation/New-RandomPassword.README.md))
* [New-RandomPIN](Module/LazyAdmin/New-RandomPIN.ps1) - Generate a random PIN with a freely definable number of numbers ([view documentation](Documentation/New-RandomPIN.README.md))
* [Search-StringInFiles](Module/LazyAdmin/Search-StringInFiles.ps1) - Find a string in one or multiple files ([view documentation](Documentation/Search-StringInFiles.README.md))
* [Test-IsFileBinary](Module/LazyAdmin/Test-IsFileBinary.ps1) - Test if a file is binary or just a text file ([view documentation](Documentation/Test-IsFileBinary.README.md))
* [Update-StringInFiles](Module/LazyAdmin/Update-StringInFiles.ps1) - Replace a string in one or multiple files ([view documentation](Documentation/Update-StringInFiles.README.md))

### ModernConsole 

Download the folder [Module/ModernConsole](Module/ModernConsole) and save it under `C:\Users\%username%\Documents\WindowsPowerShell\Modules`. Then run the command `Import-Module ModernConsole`

Available Functions:

* Startscreen with informations about the user and computer (overwrites `Clear-Console`)
* Short paths - shows drive/network share and the current folder (overwrites `prompt`)

![Screenshot](/Documentation/ModernConsole.png?raw=true)

## Scripts

* [Convert-Subnetmask.ps1](Scripts/Convert-Subnetmask.ps1) - Convert a subnetmask to CIDR and vise versa ([view documentation](Documentation/Convert-Subnetmask.README.md))
* [Get-InstalledSoftware.ps1](Scripts/Get-InstalledSoftware.ps1) - Get all installed software with DisplayName, Publisher and UninstallString ([view documentation](Documentation/Get-InstalledSoftware.README.md))
* [Get-WindowsProductKey.ps1](Scripts/Get-WindowsProductKey.ps1) - Get the Windows product key and some informations about the system ([view documentation](Documentation/Get-WindowsProductKey.README.md))
* [Get-WLANProfile.ps1](Scripts/Get-WLANProfile.ps1) - Get all WLAN-Profiles on your **local system**, include password ([view documentation](Documentation/Get-WLANProfile.README.md))
* [New-IPv4Subnet](Scripts/New-IPv4Subnet.ps1) - Calculate a subnet based on an IP-Address within the subnet and the subnetmask/CIDR ([view documentation](Documentation/New-IPv4Subnet.README.md))
* [New-RandomPassword.ps1](Scripts/New-RandomPassword.ps1) - Generate a random password with a freely definable number of chracters ([view documentation](Documentation/New-RandomPassword.README.md))
* [New-RandomPIN.ps1](Scripts/New-RandomPIN.ps1) - Generate a random PIN with a freely definable number of numbers ([view documentation](Documentation/New-RandomPIN.README.md))
* [Search-StringInFiles.ps1](Scripts/Search-StringInFiles.ps1) - Find a string in one or multiple files ([view documentation](Documentation/Search-StringInFiles.README.md))
* [Test-IsFileBinary.ps1](Scripts/Test-IsFileBinary.ps1) - Test if a file is binary or just a text file ([view documentation](Documentation/Test-IsFileBinary.README.md))
* [Update-StringInFiles.ps1](Scripts/Update-StringInFiles.ps1) - Replace a string in one or multiple files ([view documentation](Documentation/Update-StringInFiles.README.md))

## Snippets

* [custom_psobject.ps1](Snippets/custom_psobject.ps1) - Built custom PSObject to process or return as result
* [get_console_colors.ps1](Snippets/get_console_colors.ps1) - List all foreground and background console colors with preview
* [get_sourcecode_of_a_function.ps1](Snippets/get_sourcecode_of_a_function.ps1) - Get the sourcecode of an existing function
* [press_any_key_to_continue.ps1](Snippets/press_any_key_to_continue.ps1) - Wait for user interaction e.g. at the end of a script
* [self_elevating_script.ps1](Snippets/self_elevating_script.ps1) - Self elevate a PowerShell script/console with parameter 
* [send_mail_message.ps1](Snippets/send_mail_message.ps1) - Send a mail message via PowerShell
* [use_exchange_2010_management_shell.ps1](Snippets/use_exchange_2010_management_shell.ps1) - Use Exchange 2010 Management Shell in script

## Templates

* [Default.ps1](Templates/Default.ps1) - Default template for all new scripts
* [Default.README.md](Templates/Default.README.md) - Default template for script/function documentation on GitHub
* [RunspacePool.ps1](Templates/RunspacePool.ps1) - Run code asynchron in a RunspacePool - more efficient than than PSJobs
