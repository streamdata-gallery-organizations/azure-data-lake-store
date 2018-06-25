---
name: Azure Data Lake Store
x-slug: azure-data-lake-store
description: The Data Lake store provides a single repository where you can capture
  data of any size type and speed simply without forcing changes to your application
  as the data scales. In the store, data can be shared for collaboration with enterprise-grade
  security. It is also designed for high-performance processing and analytics from
  HDFS applications (ie. Azure HDInsight, Data Lake analytics service, Hortonworks,
  Cloudera, MapR) and tools, including support for low latency workloads. For example,
  data can be ingested in real-time from sensors and devices for IoT solutions, or
  from online shopping websites into the store without the restriction of fixed limits
  on account or file size unlike current offerings in the market.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Azure Data Lake Store
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Data Lake Store API Firewall Rules Create Or Update
  x-api-slug: azure-data-lake-store-api
  description: Creates or updates the specified firewall rule. During update, the
    firewall rule with the specified name will be replaced with this new firewall
    rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}/firewallRules/{firewallRuleName}
  tags: Firewall Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnamefirewallrulesfirewallrulename-put-openapi.md
- name: Azure Data Lake Store API Firewall Rules Update
  x-api-slug: azure-data-lake-store-api
  description: Updates the specified firewall rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}/firewallRules/{firewallRuleName}
  tags: Firewall Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnamefirewallrulesfirewallrulename-patch-openapi.md
- name: Azure Data Lake Store API Firewall Rules Delete
  x-api-slug: azure-data-lake-store-api
  description: Deletes the specified firewall rule from the specified Data Lake Store
    account
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}/firewallRules/{firewallRuleName}
  tags: Firewall Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnamefirewallrulesfirewallrulename-delete-openapi.md
- name: Azure Data Lake Store API Firewall Rules Get
  x-api-slug: azure-data-lake-store-api
  description: Gets the specified Data Lake Store firewall rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}/firewallRules/{firewallRuleName}
  tags: Firewall Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnamefirewallrulesfirewallrulename-get-openapi.md
- name: Azure Data Lake Store API Firewall Rules List By Account
  x-api-slug: azure-data-lake-store-api
  description: Lists the Data Lake Store firewall rules within the specified Data
    Lake Store account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}/firewallRules
  tags: Firewall Rule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnamefirewallrules-get-openapi.md
- name: Azure Data Lake Store API Trusted Id Providers Create Or Update
  x-api-slug: azure-data-lake-store-api
  description: Creates or updates the specified trusted identity provider. During
    update, the trusted identity provider with the specified name will be replaced
    with this new provider
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}/trustedIdProviders/{trustedIdProviderName}
  tags: Trusted Id Provider
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnametrustedidproviderstrustedidprovidername-put-openapi.md
- name: Azure Data Lake Store API Trusted Id Providers Update
  x-api-slug: azure-data-lake-store-api
  description: Updates the specified trusted identity provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}/trustedIdProviders/{trustedIdProviderName}
  tags: Trusted Id Provider
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnametrustedidproviderstrustedidprovidername-patch-openapi.md
- name: Azure Data Lake Store API Trusted Id Providers Delete
  x-api-slug: azure-data-lake-store-api
  description: Deletes the specified trusted identity provider from the specified
    Data Lake Store account
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}/trustedIdProviders/{trustedIdProviderName}
  tags: Trusted Id Provider
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnametrustedidproviderstrustedidprovidername-delete-openapi.md
- name: Azure Data Lake Store API Trusted Id Providers Get
  x-api-slug: azure-data-lake-store-api
  description: Gets the specified Data Lake Store trusted identity provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}/trustedIdProviders/{trustedIdProviderName}
  tags: Trusted Id Provider
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnametrustedidproviderstrustedidprovidername-get-openapi.md
- name: Azure Data Lake Store API Trusted Id Providers List By Account
  x-api-slug: azure-data-lake-store-api
  description: Lists the Data Lake Store trusted identity providers within the specified
    Data Lake Store account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}/trustedIdProviders
  tags: Trusted Id Provider
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnametrustedidproviders-get-openapi.md
- name: Azure Data Lake Store API Account Create
  x-api-slug: azure-data-lake-store-api
  description: Creates the specified Data Lake Store account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{name}
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsname-put-openapi.md
- name: Azure Data Lake Store API Account Update
  x-api-slug: azure-data-lake-store-api
  description: Updates the specified Data Lake Store account information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{name}
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsname-patch-openapi.md
- name: Azure Data Lake Store API Account Delete
  x-api-slug: azure-data-lake-store-api
  description: Deletes the specified Data Lake Store account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{name}
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsname-delete-openapi.md
- name: Azure Data Lake Store API Account Get
  x-api-slug: azure-data-lake-store-api
  description: Gets the specified Data Lake Store account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{name}
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsname-get-openapi.md
- name: Azure Data Lake Store API Account Enable Key Vault
  x-api-slug: azure-data-lake-store-api
  description: Attempts to enable a user managed key vault for encryption of the specified
    Data Lake Store account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}/enableKeyVault
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnameenablekeyvault-post-openapi.md
- name: Azure Data Lake Store API Account List By Resource Group
  x-api-slug: azure-data-lake-store-api
  description: Lists the Data Lake Store accounts within a specific resource group.
    The response includes a link to the next page of results, if any.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccounts-get-openapi.md
- name: Azure Data Lake Store API Account List
  x-api-slug: azure-data-lake-store-api
  description: Lists the Data Lake Store accounts within the subscription. The response
    includes a link to the next page of results, if any.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/providers/Microsoft.DataLakeStore/accounts
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/subscriptionssubscriptionidprovidersmicrosoft-datalakestoreaccounts-get-openapi.md
- name: Azure Data Lake Store API File System Concurrent Append
  x-api-slug: azure-data-lake-store-api
  description: 'Appends to the specified file, optionally first creating the file
    if it does not yet exist. This method supports multiple concurrent appends to
    the file. NOTE: The target must not contain data added by Create or normal (serial)
    Append. ConcurrentAppend and Append cannot be used interchangeably; once a target
    file has been modified using either of these append options, the other append
    option cannot be used on the target file. ConcurrentAppend does not guarantee
    order and can result in duplicated data landing in the target file.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////WebHdfsExt/{filePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsextfilepath-post-openapi.md
- name: Azure Data Lake Store API File System Set File Expiry
  x-api-slug: azure-data-lake-store-api
  description: Sets or removes the expiration time on the specified file. This operation
    can only be executed against files. Folders are not supported.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////WebHdfsExt/{filePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsextfilepath-put-openapi.md
- name: Azure Data Lake Store API File System Check Access
  x-api-slug: azure-data-lake-store-api
  description: Checks if the specified access is available at the given path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{path}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1path-get-openapi.md
- name: Azure Data Lake Store API File System Mkdirs
  x-api-slug: azure-data-lake-store-api
  description: Creates a directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{path}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1path-put-openapi.md
- name: Azure Data Lake Store API File System Concat
  x-api-slug: azure-data-lake-store-api
  description: Concatenates the list of source files into the destination file, removing
    all source files upon success.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{destinationPath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1destinationpath-post-openapi.md
- name: Azure Data Lake Store API File System Ms Concat
  x-api-slug: azure-data-lake-store-api
  description: Concatenates the list of source files into the destination file, deleting
    all source files upon success. This method accepts more source file paths than
    the Concat method. This method and the parameters it accepts are subject to change
    for usability in an upcoming version.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{msConcatDestinationPath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1msconcatdestinationpath-post-openapi.md
- name: Azure Data Lake Store API File System List File Status
  x-api-slug: azure-data-lake-store-api
  description: Get the list of file status objects specified by the file path, with
    optional pagination parameters
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{listFilePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1listfilepath-get-openapi.md
- name: Azure Data Lake Store API File System Get Content Summary
  x-api-slug: azure-data-lake-store-api
  description: Gets the file content summary object specified by the file path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{getContentSummaryFilePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1getcontentsummaryfilepath-get-openapi.md
- name: Azure Data Lake Store API File System Get File Status
  x-api-slug: azure-data-lake-store-api
  description: Get the file status object specified by the file path.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{getFilePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1getfilepath-get-openapi.md
- name: Azure Data Lake Store API File System Append
  x-api-slug: azure-data-lake-store-api
  description: "Used for serial appends to the specified file.\_NOTE: The target must
    not contain data added by ConcurrentAppend. ConcurrentAppend and Append cannot
    be used interchangeably; once a target file has been modified using either of
    these append options, the other append option cannot be used on the target file."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{directFilePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1directfilepath-post-openapi.md
- name: Azure Data Lake Store API File System Create
  x-api-slug: azure-data-lake-store-api
  description: 'Creates a file with optionally specified content. NOTE: If content
    is provided, the resulting file cannot be modified using ConcurrentAppend.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{directFilePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1directfilepath-put-openapi.md
- name: Azure Data Lake Store API File System Open
  x-api-slug: azure-data-lake-store-api
  description: Opens and reads from the specified file.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{directFilePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1directfilepath-get-openapi.md
- name: Azure Data Lake Store API File System Set Acl
  x-api-slug: azure-data-lake-store-api
  description: Sets the Access Control List (ACL) for a file or folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{setAclFilePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1setaclfilepath-put-openapi.md
- name: Azure Data Lake Store API File System Modify Acl Entries
  x-api-slug: azure-data-lake-store-api
  description: Modifies existing Access Control List (ACL) entries on a file or folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{modifyAclFilePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1modifyaclfilepath-put-openapi.md
- name: Azure Data Lake Store API File System Remove Acl Entries
  x-api-slug: azure-data-lake-store-api
  description: Removes existing Access Control List (ACL) entries for a file or folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{removeAclFilePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1removeaclfilepath-put-openapi.md
- name: Azure Data Lake Store API File System Remove Default Acl
  x-api-slug: azure-data-lake-store-api
  description: Removes the existing Default Access Control List (ACL) of the specified
    directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{defaultAclFilePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1defaultaclfilepath-put-openapi.md
- name: Azure Data Lake Store API File System Remove Acl
  x-api-slug: azure-data-lake-store-api
  description: Removes the existing Access Control List (ACL) of the specified file
    or directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{aclFilePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1aclfilepath-put-openapi.md
- name: Azure Data Lake Store API File System Get Acl Status
  x-api-slug: azure-data-lake-store-api
  description: Gets Access Control List (ACL) entries for the specified file or directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{aclFilePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1aclfilepath-get-openapi.md
- name: Azure Data Lake Store API File System Delete
  x-api-slug: azure-data-lake-store-api
  description: Deletes the requested file or directory, optionally recursively.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{filePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1filepath-delete-openapi.md
- name: Azure Data Lake Store API File System Rename
  x-api-slug: azure-data-lake-store-api
  description: Rename a file or directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{renameFilePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1renamefilepath-put-openapi.md
- name: Azure Data Lake Store API File System Set Owner
  x-api-slug: azure-data-lake-store-api
  description: Sets the owner of a file or directory.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{setOwnerFilePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1setownerfilepath-put-openapi.md
- name: Azure Data Lake Store API File System Set Permission
  x-api-slug: azure-data-lake-store-api
  description: Sets the permission of the file or folder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////webhdfs/v1/{setPermissionFilePath}
  tags: File System
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/webhdfsv1setpermissionfilepath-put-openapi.md
- name: Azure Data Lake Store API
  x-api-slug: azure-data-lake-store-api
  description: The Data Lake store provides a single repository where you can capture
    data of any size type and speed simply without forcing changes to your application
    as the data scales. In the store, data can be shared for collaboration with enterprise-grade
    security. It is also designed for high-performance processing and analytics from
    HDFS applications (ie. Azure HDInsight, Data Lake analytics service, Hortonworks,
    Cloudera, MapR) and tools, including support for low latency workloads. For example,
    data can be ingested in real-time from sensors and devices for IoT solutions,
    or from online shopping websites into the store without the restriction of fixed
    limits on account or file size unlike current offerings in the market.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: :////
  tags: Azure Data Lake Store
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-data-lake-store/master/_listings/azure-data-lake-store/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/data-lake-store/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/data-lake-store/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/data-lake-store/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/data-lake-store/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---