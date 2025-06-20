# react-build

#
demo

## get thumb print :

az webapp config ssl list --resource-group "pocdotnetapp" --query "[].{Thumbprint:thumbprint, HostName: hostNames}" --output table

  az webapp config ssl show --resource-group pocdotnetapp --certificate-name api.pkchai.com --query thumbprint --output tsv