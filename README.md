# Restore File Share from Azure Backup to Another Storage Account

**There are 2 objectives with this lab:**
* Create Storage Account
* Backup and Restore Data


## Create Storage Account

In the first part of the lab, we need to set up our virtual machine (VM) environment and make sure we have everything in our storage container. So, lets go into our VM first. I went into my resource group (RG) and chose `vm`.

![Image](AzureSAS1.png)



That completes the first half of this lab!



## Backup and Restore Data

For the second portion of this lab, we need to allow the Azure portal to allow shared access signatures (SAS) to connect to the VM's Storage Explorer. So lets do that. 

Gointo the `pslabs` storage account again and this time, navigate to Settings > Configuration. Here, we're going to enable `Allow storage account key access`. Make sure to save your changes at the top of the screen. 

![Image](AzureSAS11.png)


Lab completed!

## Personal Notes

This lab also wasn't bad. I think it was cool just watching the storage account pop up in the VM. Feels like magic when these computers talk sometimes. It was nice to finally get my hands on SAS technology. I feel like I see SAS tokens all the time but have never worked with them. Anyway, cool.  
