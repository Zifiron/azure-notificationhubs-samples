# Notification Hubs Samples

This repository will contain sample code for Notification Hubs.

### [Push to Safari]
Sample on how to send push notifications to Safari using Azure Notification Hubs and Azure Web Sites. 

### [Push to Chrome Apps]
Sample Chrome App to demonstrate how to use Azure Notification Hubs to push to Chrome Apps. 

### [Push to SL Phone]
Azure Notification Hubs Windows Phone SDK currently does not support using WNS with Windows Phone 8.1 Silverlight apps. This sample takes you through the steps to create a Windows Phone 8.1 Silverlight app which registers with Azure Notification Hubs so that it can receive notifications via Notification Hubs. 

### [Push to WNS]
This sample is useful when you want to test the end to end flow between client app and WNS without Azure Notification Hubs in the picture. This helps in validating that your client app is set up correctly as well that you have the correct Package SID & Secret that you are configuring in the Azure Notification Hubs. In case the PNS responds with an error then you also get to see the exact error from the WNS itself providing additional information.

### [Enterprise Push Sample]
http://azure.microsoft.com/en-us/documentation/articles/notification-hubs-enterprise-push-architecture/

### [Programmatic Telemetry access]
This sample is in the form of a VSTO Excel application which uses the Notification Hubs REST API to get the telemetry data and then uses the Excel functions to populate a spreadsheet with the data as well as generate a chart of the retrieved data. 

### [PHP SDK]
This is a sample for sending notifications to Notification Hubs using PHP.

### [Python SDK]
This is a sample for sending notifications to Notification Hubs using Python.

### [Java SDK]

**The official Java SDK is now available at - [Official Java SDK]. Please refer to it going forward. This is here only for legacy reasons.**


[Official Java SDK]: https://github.com/Azure/azure-notificationhubs-java-backend
[Chrome Apps tutorial]: http://azure.microsoft.com/en-us/documentation/articles/notification-hubs-chrome-get-started/

[Enterprise Push Sample]: https://github.com/Azure/azure-notificationhubs-samples/tree/master/EnteprisePush
[Programmatic Telemetry access]: https://github.com/Azure/azure-notificationhubs-samples/tree/master/FetchNHTelemetryInExcel
[Push to Chrome Apps]: https://github.com/Azure/azure-notificationhubs-samples/tree/master/PushToChromeApps
[Push to SL Phone]: https://github.com/Azure/azure-notificationhubs-samples/tree/master/PushToSLPhoneApp
[Push to Safari]: https://github.com/Azure/azure-notificationhubs-samples/tree/master/PushToSafari
[Push to WNS]: https://github.com/Azure/azure-notificationhubs-samples/tree/master/PushToWNSDirectly
[Java SDK]: https://github.com/Azure/azure-notificationhubs-samples/tree/master/notificationhubs-rest-java
[PHP SDK]: https://github.com/Azure/azure-notificationhubs-samples/tree/master/notificationhubs-rest-php
[Python SDK]: https://github.com/Azure/azure-notificationhubs-samples/tree/master/notificationhubs-rest-python
