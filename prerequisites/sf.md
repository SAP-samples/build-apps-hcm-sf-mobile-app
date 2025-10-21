# SAP SuccessFactors Prerequisites

## Introduction

Even though we will be using a sandbox from the SAP Business Accelerator Hub throughout the tutorial, it is important to understand how to perform the integration in a real system. This exercise highlights the key steps you need to follow to set up the integration with the SAP SuccessFactors Benefits API.

## Content

1. We are going to consume the employee benefits data in the application. Employee Central Global Benefits is an integral part of Employee Central, an integrated HR core suite of tools available in the cloud. More details can be found in this [Introduction to Global Benefits](https://help.sap.com/docs/successfactors-employee-central/implementing-global-benefits/462ec1def36f4281b596358cdb9cc5b8.html).

2. Since data access will be performed through user propagation, your account must have the appropriate authorization. Having **Benefits Management** permissions is sufficient. For more information, please refer to the [Role-Based Permissions for Global Benefits](https://help.sap.com/docs/successfactors-employee-central/implementing-global-benefits/ce2a1f5916ff4ab08505264468022423.html) documentation.

3. Set up the necessary authentication as described [here](https://help.sap.com/docs/successfactors-platform/sap-successfactors-api-reference-guide-odata-v2/authentication). In this tutorial the basic authentication is used. It is shown only for demo purposes and is depricated.

4. Read specification of your API. In this case we will use [Benefit OData V2 API](https://help.sap.com/docs/successfactors-platform/sap-successfactors-api-reference-guide-odata-v2/benefit).

