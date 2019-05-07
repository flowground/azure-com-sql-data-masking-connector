# ![LOGO](logo.png) Azure SQL Database Datamasking Policies and Rules **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure SQL Database Datamasking Policies and Rules API (version 2014-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/sql-dataMasking/2014-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:02+03:00

## API Description

Provides create, read, update and delete functionality for Azure SQL Database datamasking policies and rules.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets a database data masking policy.

*Tags:* `DataMaskingPolicies`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database.
* `dataMaskingPolicyName` - _required_ - The name of the database for which the data masking rule applies.
    Possible values: Default.

### Creates or updates a database data masking policy

*Tags:* `DataMaskingPolicies`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database.
* `dataMaskingPolicyName` - _required_ - The name of the database for which the data masking rule applies.
    Possible values: Default.

### Gets a list of database data masking rules.

*Tags:* `DataMaskingRules`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database.
* `dataMaskingPolicyName` - _required_ - The name of the database for which the data masking rule applies.
    Possible values: Default.

### Creates or updates a database data masking rule.

*Tags:* `DataMaskingRules`

#### Input Parameters
* `api-version` - _required_ - The API version to use for the request.
* `subscriptionId` - _required_ - The subscription ID that identifies an Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `serverName` - _required_ - The name of the server.
* `databaseName` - _required_ - The name of the database.
* `dataMaskingPolicyName` - _required_ - The name of the database for which the data masking rule applies.
    Possible values: Default.
* `dataMaskingRuleName` - _required_ - The name of the data masking rule.

## License

**flow**ground :- Telekom iPaaS / azure-com-sql-data-masking-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
