# ![LOGO](logo.png) ApiManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ApiManagementClient API (version 2018-06-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/apimanagement-apimnotifications/2018-06-01-preview/swagger.json<br/>
Generated at: 2019-06-11T18:13:14+03:00

## API Description

Use these REST APIs for performing operations on who is going to receive notifications associated with your Azure API Management deployment.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists a collection of properties defined within a service instance.

*Tags:* `Notification`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `$top` - _optional_ - Number of records to return.
* `$skip` - _optional_ - Number of records to skip.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the details of the Notification specified by its identifier.

*Tags:* `Notification`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `notificationName` - _required_ - Notification Name Identifier.
    Possible values: RequestPublisherNotificationMessage, PurchasePublisherNotificationMessage, NewApplicationNotificationMessage, BCC, NewIssuePublisherNotificationMessage, AccountClosedPublisher, QuotaLimitApproachingPublisherNotificationMessage.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Create or Update API Management publisher notification.

*Tags:* `Notification`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `notificationName` - _required_ - Notification Name Identifier.
    Possible values: RequestPublisherNotificationMessage, PurchasePublisherNotificationMessage, NewApplicationNotificationMessage, BCC, NewIssuePublisherNotificationMessage, AccountClosedPublisher, QuotaLimitApproachingPublisherNotificationMessage.
* `If-Match` - _optional_ - ETag of the Entity. Not required when creating an entity, but required when updating an entity.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the list of the Notification Recipient Emails subscribed to a notification.

*Tags:* `NotificationRecipientEmail`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `notificationName` - _required_ - Notification Name Identifier.
    Possible values: RequestPublisherNotificationMessage, PurchasePublisherNotificationMessage, NewApplicationNotificationMessage, BCC, NewIssuePublisherNotificationMessage, AccountClosedPublisher, QuotaLimitApproachingPublisherNotificationMessage.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Removes the email from the list of Notification.

*Tags:* `NotificationRecipientEmail`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `notificationName` - _required_ - Notification Name Identifier.
    Possible values: RequestPublisherNotificationMessage, PurchasePublisherNotificationMessage, NewApplicationNotificationMessage, BCC, NewIssuePublisherNotificationMessage, AccountClosedPublisher, QuotaLimitApproachingPublisherNotificationMessage.
* `email` - _required_ - Email identifier.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Determine if Notification Recipient Email subscribed to the notification.

*Tags:* `NotificationRecipientEmail`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `notificationName` - _required_ - Notification Name Identifier.
    Possible values: RequestPublisherNotificationMessage, PurchasePublisherNotificationMessage, NewApplicationNotificationMessage, BCC, NewIssuePublisherNotificationMessage, AccountClosedPublisher, QuotaLimitApproachingPublisherNotificationMessage.
* `email` - _required_ - Email identifier.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Adds the Email address to the list of Recipients for the Notification.

*Tags:* `NotificationRecipientEmail`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `notificationName` - _required_ - Notification Name Identifier.
    Possible values: RequestPublisherNotificationMessage, PurchasePublisherNotificationMessage, NewApplicationNotificationMessage, BCC, NewIssuePublisherNotificationMessage, AccountClosedPublisher, QuotaLimitApproachingPublisherNotificationMessage.
* `email` - _required_ - Email identifier.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the list of the Notification Recipient User subscribed to the notification.

*Tags:* `NotificationRecipientUser`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `notificationName` - _required_ - Notification Name Identifier.
    Possible values: RequestPublisherNotificationMessage, PurchasePublisherNotificationMessage, NewApplicationNotificationMessage, BCC, NewIssuePublisherNotificationMessage, AccountClosedPublisher, QuotaLimitApproachingPublisherNotificationMessage.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Removes the API Management user from the list of Notification.

*Tags:* `NotificationRecipientUser`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `notificationName` - _required_ - Notification Name Identifier.
    Possible values: RequestPublisherNotificationMessage, PurchasePublisherNotificationMessage, NewApplicationNotificationMessage, BCC, NewIssuePublisherNotificationMessage, AccountClosedPublisher, QuotaLimitApproachingPublisherNotificationMessage.
* `userId` - _required_ - User identifier. Must be unique in the current API Management service instance.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Determine if the Notification Recipient User is subscribed to the notification.

*Tags:* `NotificationRecipientUser`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `notificationName` - _required_ - Notification Name Identifier.
    Possible values: RequestPublisherNotificationMessage, PurchasePublisherNotificationMessage, NewApplicationNotificationMessage, BCC, NewIssuePublisherNotificationMessage, AccountClosedPublisher, QuotaLimitApproachingPublisherNotificationMessage.
* `userId` - _required_ - User identifier. Must be unique in the current API Management service instance.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Adds the API Management User to the list of Recipients for the Notification.

*Tags:* `NotificationRecipientUser`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `serviceName` - _required_ - The name of the API Management service.
* `notificationName` - _required_ - Notification Name Identifier.
    Possible values: RequestPublisherNotificationMessage, PurchasePublisherNotificationMessage, NewApplicationNotificationMessage, BCC, NewIssuePublisherNotificationMessage, AccountClosedPublisher, QuotaLimitApproachingPublisherNotificationMessage.
* `userId` - _required_ - User identifier. Must be unique in the current API Management service instance.
* `api-version` - _required_ - Version of the API to be used with the client request.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-apimanagement-apimnotifications-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
