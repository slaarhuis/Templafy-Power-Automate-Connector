# Templafy's Power Automate Connector
for use with Microsoft Power Automate flows and Power Apps

Read more about uploading/downloading these files on this blog: 
https://philcole.org/post/environment-specific-custom-connector-endpoints/

## Installation on Microsoft (test) tenant
1. Install the pacon tool following the instructions from this page: https://philcole.org/post/environment-specific-custom-connector-endpoints/
2. Create a folder on your drive and download all files of the connector (this Github repo) to that folder
3. Go to your CMD and navigate to the created folder (using cd command)
4. Enter paconn login and follow the instructions
5. Enter paconn create --api-prop .\apiProperties.json --api-def .\apiDefinition.swagger.json
6. Select the right environment
7. Connector is created on your own tenant, find the connector in https://make.powerapps.com/ under 'Custom connectors' in the navigation bar on the left
8. Edit the connector settings. Upload the logo as part of this package.
