Registers Azure resource manager virtual machines with Automation DSC service.
==============================================================================

            

This runbook registers Azure resource manager virtual machines with Automation DSC service. These can either be Windows or Linux virtual machines that are supported with DSC.



You can specify the whole subscription, a specific resource group, or an individual VM that you want to register with the automation account. This runbook does not apply a specific node configuration as this can be done separately through the DSC Node experience
 in the automation account or through the PowerShell cmdlets. The runbook depends on having a RunAs credential set up in your automation account.


 

 ![Image](https://github.com/azureautomation/registers-azure-resource-manager-virtual-machines-with-automation-dsc-service./raw/master/Register-VMDSC.png)

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
