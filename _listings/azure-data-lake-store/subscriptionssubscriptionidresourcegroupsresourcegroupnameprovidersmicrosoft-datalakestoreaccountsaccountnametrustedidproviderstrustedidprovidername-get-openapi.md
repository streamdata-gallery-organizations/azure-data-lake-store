---
swagger: "2.0"
x-collection-name: Azure Data Lake Store
x-complete: 0
info:
  title: Azure Data Lake Store API Trusted Id Providers Get
  description: Gets the specified Data Lake Store trusted identity provider.
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnamefirewallrulesfirewallrulename-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnamefirewallrulesfirewallrulename-patch
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnamefirewallrulesfirewallrulename-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnamefirewallrulesfirewallrulename-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnamefirewallrules-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnametrustedidproviderstrustedidprovidername-put
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnametrustedidproviderstrustedidprovidername-patch
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnametrustedidproviderstrustedidprovidername-delete
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnametrustedidproviderstrustedidprovidername-get
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