# bv-synapse

This project will deploy a customized Azure Synapse installation with specific settings for Bitvore Cellenus Data.  The workspace accounts are RBAC's to the storage
as part of the deploy. One final RBAC post install is required. 

After install is complete you must add your user account as a blob storage owner to the newly created storage account. The new new storage account is called:
stg[workspaceandstorageaccountname]
 
 workspaceandstorageaccountname is the core parameter required during install. It creates a Synapse workspace named ws[workspaceandstorageaccountname] and a storage account
 named stg[workspaceandstorageaccountname]
 
 [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ffrankartartale%2Fbv-synapse%2Fmain%2Fazuredeploy.json)
