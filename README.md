# Disclaimer
The information contained in this README.md file and any accompanying materials (including, but not limited to, scripts, sample codes, etc.) are provided "AS-IS" and "WITH ALL FAULTS." Any estimated pricing information is provided solely for demonstration purposes and does not represent final pricing and Microsoft assumes no liability arising from your use of the information. Microsoft makes NO GUARANTEES OR WARRANTIES OF ANY KIND, WHETHER EXPRESSED OR IMPLIED, in providing this information, including any pricing information.

# Introduction
This project implements the Contoso Customer Service Rewards Lookup & Consumption Application with App Service Environment.

# Get Started
To create this, you will need to follow build the application. The applications are build via a process on the [source repo](https://github.com/msft-davidlee/contoso-customer-service-app) and deploy to [shared services](https://github.com/msft-davidlee/az-internal-shared-services). Please review both as pre-reqs project before proceeding further here. Next, use your Azure subscription and also a AAD instance that you control and follow the steps below.

## Secrets
| Name | Comments |
| --- | --- |
| MS_AZURE_CREDENTIALS | <pre>{<br/>&nbsp;&nbsp;&nbsp;&nbsp;"clientId": "",<br/>&nbsp;&nbsp;&nbsp;&nbsp;"clientSecret": "", <br/>&nbsp;&nbsp;&nbsp;&nbsp;"subscriptionId": "",<br/>&nbsp;&nbsp;&nbsp;&nbsp;"tenantId": "" <br/>}</pre> |
| PREFIX | mytodos - or whatever name you would like for all your resources |
| RESOURCE_GROUP | todo - or whatever name you give to the resource group |
| AAD_CLIENT_ID | Client Id |
| AAD_CLIENT_SECRET | Client Secret |
| AAD_DOMAIN | replace "something." with the correct domain something.onmicrosoft.com  |
| AAD_TENANT_ID | Tenant Id |
| BUILD_ACCOUNT_NAME | Storage Account name in your subscriptions where the zipped version of the files are located. |
| SQLPASSWORD | SQL password that you want to use |

## Have an issue?
You are welcome to create an issue if you need help but please note that there is no timeline to answer or resolve any issues you have with the contents of this project. Use the contents of this project at your own risk! If you are interested to volunteer to maintain this, please feel free to reach out to be added as a contributor and send Pull Requests (PR).
