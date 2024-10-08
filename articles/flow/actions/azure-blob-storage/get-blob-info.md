# Get Blob info

Gets detailed information for a specific blob in an Azure Blob container. Use this action if you need properties of a particular blob in a container.

![img](https://profitbasedocs.blob.core.windows.net/flowimages/get-blob-info.png)



## Properties

| Name             | Type      |Description                                             |
|------------------|-----------|--------------------------------------------------------|
| Title |   |  |
| Connection       | Required  | The Azure Blob Container Connection. Choose either 1. A [SAS URI](https://learn.microsoft.com/en-us/azure/storage/common/storage-sas-overview) to an Azure Blob container or 2. A Storage account connection string and container name.       |
| Blob name | Required | The name of the blob from the list. |
| Result variable name | Required | The name of the Flow variable that contains the list of the blob properties. |
| Description | Optional | Additional notes or comments about the action or configuration.  |




