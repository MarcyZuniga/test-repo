# test-repo
test-repo
Introduction
TODO: This is a list of scipts that displays the assets. The object is to list every service that is running when working on the cloud and query resources.

Build and Test
TODO: Run script that displays project name, sku, tenantId, kind, created time, location, and resource group.

Az graph query -q "Resources | project sku, name, kind, properties.creationTime, properties.createdAt, location, resourceGroup | limit 100"