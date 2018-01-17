# acs-aks-migrate
⚒ Script to migrate from ACS Kubernetes clusters to ACS or AKS cluster

__USE IT ON YOUR OWN RISK - DO NOT USE IN PRODUCTION__

* Set the following environment variables

```bash
AZURE_SUBSCRIPTION_ID=
AZURE_TENANT_ID=
AZURE_CLIENT_ID=
AZURE_CLIENT_SECRET=
DESTINATION_CLUSTERNAME=
DESTINATION_RESOURCEGROUP=
DESTINATION_STORAGEACCOUNT=
DESTINATION_STORAGEACCOUNT_CONTAINER=
DESTINATION_MANAGED_DISK=
SOURCE_BLOB=
SOURCE_STORAGEACCOUNT_CONTAINER=
#SOURCE_SNAPSHOT=''
SOURCE_STORAGEACCOUNT=
SOURCE_STORAGEACCOUNT_KEY=
```
* Run script

```bash
bash migrate.sh
```