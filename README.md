Deploy a SQL Server VM with Striped Disks in Windows Azure
==========================================================

            

[Windows Azure Scripting Center](http://www.windowsazure.com/en-us/documentation/scripts) |
[Get Started with Windows Azure PowerShell](http://go.microsoft.com/fwlink/?linkid=320929&clcid=0x409) |
[Windows Azure Infrastructure Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=infrastructure&service=all)

Description

Adds a VM to the active subscription, based on SQL Server 2012 on Windows Server 2012 gallery image.


Adds four disks to the VM and stripes them into two pools. Formats them for use, creates a database, putting the data files on one volume and the log files on the other.


Demonstrates the use of PowerShell scripts to create VMs and Disks, but further demonstrates the use of Remote PowerShell Scripting - running a script on your desktop that automates a Windows Azure VM's environment.

Example
 
Scenario
You need to configure SQL Server with the data files and log files on separate high performance volumes.
Requirements

  *  PowerShell Version 3.0 
  *  Windows Azure PowerShell 0.6.18 
See Also

  *  [Windows Azure Infrastructure Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=infrastructure&service=all)

Script Content

The content of the script is reproduced below

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
