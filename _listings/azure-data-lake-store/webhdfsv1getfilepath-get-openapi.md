---
swagger: "2.0"
x-collection-name: Azure Data Lake Store
x-complete: 0
info:
  title: Azure Data Lake Store API File System Get File Status
  description: Get the file status object specified by the file path.
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
    put:
      summary: File System Set File Expiry
      description: Sets or removes the expiration time on the specified file. This
        operation can only be executed against files. Folders are not supported.
      operationId: FileSystem_SetFileExpiry
      x-api-path-slug: webhdfsextfilepath-put
      parameters:
      - in: query
        name: expireTime
        description: The time that the file will expire, corresponding to the ExpiryOption
          that was set
      - in: query
        name: expiryOption
        description: 'Indicates the type of expiration to use for the file: 1'
      - in: path
        name: filePath
        description: The Data Lake Store path (starting with /) of the file on which
          to set or remove the expiration time
      - in: query
        name: No Name
      - in: query
        name: op
        description: The constant value for the operation
      responses:
        200:
          description: OK
      tags:
      - File System
  /webhdfs/v1/{path}:
    get:
      summary: File System Check Access
      description: Checks if the specified access is available at the given path.
      operationId: FileSystem_CheckAccess
      x-api-path-slug: webhdfsv1path-get
      parameters:
      - in: query
        name: fsaction
        description: File system operation read/write/execute in string form, matching
          regex pattern [rwx-]{3}
      - in: query
        name: No Name
      - in: query
        name: op
        description: The constant value for the operation
      - in: path
        name: path
        description: The Data Lake Store path (starting with /) of the file or directory
          for which to check access
      responses:
        200:
          description: OK
      tags:
      - File System
    put:
      summary: File System Mkdirs
      description: Creates a directory.
      operationId: FileSystem_Mkdirs
      x-api-path-slug: webhdfsv1path-put
      parameters:
      - in: query
        name: No Name
      - in: query
        name: op
        description: The constant value for the operation
      - in: path
        name: path
        description: The Data Lake Store path (starting with /) of the directory to
          create
      - in: query
        name: permission
        description: Optional octal permission with which the directory should be
          created
      responses:
        200:
          description: OK
      tags:
      - File System
  /webhdfs/v1/{destinationPath}:
    post:
      summary: File System Concat
      description: Concatenates the list of source files into the destination file,
        removing all source files upon success.
      operationId: FileSystem_Concat
      x-api-path-slug: webhdfsv1destinationpath-post
      parameters:
      - in: path
        name: destinationPath
        description: The Data Lake Store path (starting with /) of the destination
          file resulting from the concatenation
      - in: query
        name: No Name
      - in: query
        name: op
        description: The constant value for the operation
      - in: query
        name: sources
        description: A list of comma separated Data Lake Store paths (starting with
          /) of the files to concatenate, in the order in which they should be concatenated
      responses:
        200:
          description: OK
      tags:
      - File System
  /webhdfs/v1/{msConcatDestinationPath}:
    post:
      summary: File System Ms Concat
      description: Concatenates the list of source files into the destination file,
        deleting all source files upon success. This method accepts more source file
        paths than the Concat method. This method and the parameters it accepts are
        subject to change for usability in an upcoming version.
      operationId: FileSystem_MsConcat
      x-api-path-slug: webhdfsv1msconcatdestinationpath-post
      parameters:
      - in: query
        name: deleteSourceDirectory
        description: Indicates that as an optimization instead of deleting each individual
          source stream, delete the source stream folder if all streams are in the
          same folder instead
      - in: path
        name: msConcatDestinationPath
        description: The Data Lake Store path (starting with /) of the destination
          file resulting from the concatenation
      - in: query
        name: No Name
      - in: query
        name: op
        description: The constant value for the operation
      - in: body
        name: streamContents
        description: A list of Data Lake Store paths (starting with /) of the source
          files
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - File System
  /webhdfs/v1/{listFilePath}:
    get:
      summary: File System List File Status
      description: Get the list of file status objects specified by the file path,
        with optional pagination parameters
      operationId: FileSystem_ListFileStatus
      x-api-path-slug: webhdfsv1listfilepath-get
      parameters:
      - in: query
        name: listAfter
        description: Gets or sets the item or lexographical index after which to begin
          returning results
      - in: query
        name: listBefore
        description: Gets or sets the item or lexographical index before which to
          begin returning results
      - in: path
        name: listFilePath
        description: The Data Lake Store path (starting with /) of the directory to
          list
      - in: query
        name: listSize
        description: Gets or sets the number of items to return
      - in: query
        name: No Name
      - in: query
        name: op
        description: The constant value for the operation
      - in: query
        name: tooId
        description: An optional switch to return friendly names in place of owner
          and group
      responses:
        200:
          description: OK
      tags:
      - File System
  /webhdfs/v1/{getContentSummaryFilePath}:
    get:
      summary: File System Get Content Summary
      description: Gets the file content summary object specified by the file path.
      operationId: FileSystem_GetContentSummary
      x-api-path-slug: webhdfsv1getcontentsummaryfilepath-get
      parameters:
      - in: path
        name: getContentSummaryFilePath
        description: The Data Lake Store path (starting with /) of the file for which
          to retrieve the summary
      - in: query
        name: No Name
      - in: query
        name: op
        description: The constant value for the operation
      responses:
        200:
          description: OK
      tags:
      - File System
  /webhdfs/v1/{getFilePath}:
    get:
      summary: File System Get File Status
      description: Get the file status object specified by the file path.
      operationId: FileSystem_GetFileStatus
      x-api-path-slug: webhdfsv1getfilepath-get
      parameters:
      - in: path
        name: getFilePath
        description: The Data Lake Store path (starting with /) of the file or directory
          for which to retrieve the status
      - in: query
        name: No Name
      - in: query
        name: op
        description: The constant value for the operation
      - in: query
        name: tooId
        description: An optional switch to return friendly names in place of owner
          and group
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