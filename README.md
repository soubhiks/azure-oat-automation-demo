# azure-oat-automation-demo

Steps to follow using Powershell

Prerequisites: </br>

1. **Jenkins** </br>
   a. Install Jenkins </br>
   b. Create a Pipeline job, which should run from a windows node 
   

2. **PowerShell** </br>
   a. Install Powershell-Get module </br>
      `Install-Module PowerShellGet - Force `
   
   b. Check if Poweshell-Get is properly installed </br>
      `Get-Module -Name PowerShellGet -ListAvailable | Select-Object Name,Version,Path` 
   
   c. Install Azure PowerShell module </br>
      `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned`  </br>
      `Install-Module -Name AzureRM -AllowClobber`


