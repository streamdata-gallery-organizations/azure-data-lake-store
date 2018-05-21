---
swagger: "2.0"
x-collection-name: Azure Data Lake Store
x-complete: 0
info:
  title: Azure Data Lake Store API File System Concurrent Append
  description: 'Appends to the specified file, optionally first creating the file
    if it does not yet exist. This method supports multiple concurrent appends to
    the file. NOTE: The target must not contain data added by Create or normal (serial)
    Append. ConcurrentAppend and Append cannot be used interchangeably; once a target
    file has been modified using either of these append options, the other append
    option cannot be used on the target file. ConcurrentAppend does not guarantee
    order and can result in duplicated data landing in the target file.'
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}/firewallRules/{firewallRuleName}
  : put:
      summary: Firewall Rules Create Or Update
      description: Creates or updates the specified firewall rule. During update,
        the firewall rule with the specified name will be replaced with this new firewall
        rule.
      operationId: FirewallRules_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdatalakestoreaccountsaccountnamefirewallrulesfirewallrulename-put
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Store account to add or replace the
          firewall rule
      - in: path
        name: firewallRuleName
        description: The name of the firewall rule to create or update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to create or update the firewall rule
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Store account
      responses:
        200:
          description: OK
      tags:
      - Firewall Rule
    patch:
      summary: Firewall Rules Update
      description: Updates the specified firewall rule.
      operationId: FirewallRules_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdatalakestoreaccountsaccountnamefirewallrulesfirewallrulename-patch
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Store account to which to update the
          firewall rule
      - in: path
        name: firewallRuleName
        description: The name of the firewall rule to update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to update the firewall rule
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Store account
      responses:
        200:
          description: OK
      tags:
      - Firewall Rule
    delete:
      summary: Firewall Rules Delete
      description: Deletes the specified firewall rule from the specified Data Lake
        Store account
      operationId: FirewallRules_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdatalakestoreaccountsaccountnamefirewallrulesfirewallrulename-delete
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Store account from which to delete
          the firewall rule
      - in: path
        name: firewallRuleName
        description: The name of the firewall rule to delete
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Store account
      responses:
        200:
          description: OK
      tags:
      - Firewall Rule
    get:
      summary: Firewall Rules Get
      description: Gets the specified Data Lake Store firewall rule.
      operationId: FirewallRules_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdatalakestoreaccountsaccountnamefirewallrulesfirewallrulename-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Store account from which to get the
          firewall rule
      - in: path
        name: firewallRuleName
        description: The name of the firewall rule to retrieve
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Store account
      responses:
        200:
          description: OK
      tags:
      - Firewall Rule
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}/firewallRules
  : get:
      summary: Firewall Rules List By Account
      description: Lists the Data Lake Store firewall rules within the specified Data
        Lake Store account.
      operationId: FirewallRules_ListByAccount
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdatalakestoreaccountsaccountnamefirewallrules-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Store account from which to get the
          firewall rules
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Store account
      responses:
        200:
          description: OK
      tags:
      - Firewall Rule
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}/trustedIdProviders/{trustedIdProviderName}
  : put:
      summary: Trusted Id Providers Create Or Update
      description: Creates or updates the specified trusted identity provider. During
        update, the trusted identity provider with the specified name will be replaced
        with this new provider
      operationId: TrustedIdProviders_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdatalakestoreaccountsaccountnametrustedidproviderstrustedidprovidername-put
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Store account to add or replace the
          trusted identity provider
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to create or replace the trusted identity
          provider
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Store account
      - in: path
        name: trustedIdProviderName
        description: The name of the trusted identity provider
      responses:
        200:
          description: OK
      tags:
      - Trusted Id Provider
    patch:
      summary: Trusted Id Providers Update
      description: Updates the specified trusted identity provider.
      operationId: TrustedIdProviders_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdatalakestoreaccountsaccountnametrustedidproviderstrustedidprovidername-patch
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Store account to which to update the
          trusted identity provider
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to update the trusted identity provider
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Store account
      - in: path
        name: trustedIdProviderName
        description: The name of the trusted identity provider
      responses:
        200:
          description: OK
      tags:
      - Trusted Id Provider
    delete:
      summary: Trusted Id Providers Delete
      description: Deletes the specified trusted identity provider from the specified
        Data Lake Store account
      operationId: TrustedIdProviders_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdatalakestoreaccountsaccountnametrustedidproviderstrustedidprovidername-delete
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Store account from which to delete
          the trusted identity provider
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Store account
      - in: path
        name: trustedIdProviderName
        description: The name of the trusted identity provider to delete
      responses:
        200:
          description: OK
      tags:
      - Trusted Id Provider
    get:
      summary: Trusted Id Providers Get
      description: Gets the specified Data Lake Store trusted identity provider.
      operationId: TrustedIdProviders_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdatalakestoreaccountsaccountnametrustedidproviderstrustedidprovidername-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Store account from which to get the
          trusted identity provider
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Store account
      - in: path
        name: trustedIdProviderName
        description: The name of the trusted identity provider to retrieve
      responses:
        200:
          description: OK
      tags:
      - Trusted Id Provider
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}/trustedIdProviders
  : get:
      summary: Trusted Id Providers List By Account
      description: Lists the Data Lake Store trusted identity providers within the
        specified Data Lake Store account.
      operationId: TrustedIdProviders_ListByAccount
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdatalakestoreaccountsaccountnametrustedidproviders-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Store account from which to get the
          trusted identity providers
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Store account
      responses:
        200:
          description: OK
      tags:
      - Trusted Id Provider
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{name}:
    put:
      summary: Account Create
      description: Creates the specified Data Lake Store account.
      operationId: Account_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdatalakestoreaccountsname-put
      parameters:
      - in: path
        name: name
        description: The name of the Data Lake Store account to create
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to create the Data Lake Store account
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Store account
      responses:
        200:
          description: OK
      tags:
      - Account
    patch:
      summary: Account Update
      description: Updates the specified Data Lake Store account information.
      operationId: Account_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdatalakestoreaccountsname-patch
      parameters:
      - in: path
        name: name
        description: The name of the Data Lake Store account to update
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to update the Data Lake Store account
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Store account
      responses:
        200:
          description: OK
      tags:
      - Account
    delete:
      summary: Account Delete
      description: Deletes the specified Data Lake Store account.
      operationId: Account_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdatalakestoreaccountsname-delete
      parameters:
      - in: path
        name: name
        description: The name of the Data Lake Store account to delete
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Store account
      responses:
        200:
          description: OK
      tags:
      - Account
    get:
      summary: Account Get
      description: Gets the specified Data Lake Store account.
      operationId: Account_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdatalakestoreaccountsname-get
      parameters:
      - in: path
        name: name
        description: The name of the Data Lake Store account to retrieve
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Store account
      responses:
        200:
          description: OK
      tags:
      - Account
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}/enableKeyVault
  : post:
      summary: Account Enable Key Vault
      description: Attempts to enable a user managed key vault for encryption of the
        specified Data Lake Store account.
      operationId: Account_EnableKeyVault
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdatalakestoreaccountsaccountnameenablekeyvault-post
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Store account to attempt to enable
          the Key Vault for
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Store account
      responses:
        200:
          description: OK
      tags:
      - Account
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts:
    get:
      summary: Account List By Resource Group
      description: Lists the Data Lake Store accounts within a specific resource group.
        The response includes a link to the next page of results, if any.
      operationId: Account_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdatalakestoreaccounts-get
      parameters:
      - in: query
        name: $count
        description: A Boolean value of true or false to request a count of the matching
          resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Store account(s)
      responses:
        200:
          description: OK
      tags:
      - Account
  /subscriptions/{subscriptionId}/providers/Microsoft.DataLakeStore/accounts:
    get:
      summary: Account List
      description: Lists the Data Lake Store accounts within the subscription. The
        response includes a link to the next page of results, if any.
      operationId: Account_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftdatalakestoreaccounts-get
      parameters:
      - in: query
        name: $count
        description: The Boolean value of true or false to request a count of the
          matching resources included with the resources in the response, e
      - in: query
        name: $filter
        description: OData filter
      - in: query
        name: $orderby
        description: OrderBy clause
      - in: query
        name: $select
        description: OData Select statement
      - in: query
        name: $skip
        description: The number of items to skip over before returning elements
      - in: query
        name: $top
        description: The number of items to return
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Account
  /WebHdfsExt/{filePath}:
    post:
      summary: File System Concurrent Append
      description: 'Appends to the specified file, optionally first creating the file
        if it does not yet exist. This method supports multiple concurrent appends
        to the file. NOTE: The target must not contain data added by Create or normal
        (serial) Append. ConcurrentAppend and Append cannot be used interchangeably;
        once a target file has been modified using either of these append options,
        the other append option cannot be used on the target file. ConcurrentAppend
        does not guarantee order and can result in duplicated data landing in the
        target file.'
      operationId: FileSystem_ConcurrentAppend
      x-api-path-slug: webhdfsextfilepath-post
      parameters:
      - in: query
        name: appendMode
        description: Indicates the concurrent append call should create the file if
          it doesnt exist or just open the existing file for append
      - in: path
        name: filePath
        description: The Data Lake Store path (starting with /) of the file to which
          to append using concurrent append
      - in: query
        name: No Name
      - in: query
        name: op
        description: The constant value for the operation
      - in: body
        name: streamContents
        description: The file contents to include when appending to the file
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: syncFlag
        description: Optionally indicates what to do after completion of the concurrent
          append
      - in: header
        name: Transfer-Encoding
        description: Indicates the data being sent to the server is being streamed
          in chunks
      responses:
        200:
          description: OK
      tags:
      - File System
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---