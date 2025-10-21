# Landscape Setup

## Introduction

In this exercise, you will learn how to set up SAP BTP Subaccount.

## Content

In this mission you can use either an SAP Trial account or setup the existing one.

### Trial Account Setup

1. Create a trial account as described in the [Get an Account on SAP BTP Trial](https://developers.sap.com/tutorials/hcp-create-trial-account..html) tutorial.

2. Run the booster as described in the [Set Up SAP Build Apps (with Booster) on SAP BTP Trial Account](https://developers.sap.com/tutorials/build-apps-trial-booster..html) tutorial.

### Manual Subaccount Setup

1. You have to be an administrator for you subaccount.

2. Manage entitlements for your global account as described in the [Manage Entitlements Using the Cockpit](https://developers.sap.com/tutorials/btp-cockpit-entitlements..html) tutoral.

    Entitlements/Quota required in your SAP Business Technology Platform Account:

    | Service                           | Plan        | Number of instances |
    | --------------------------------- | ----------- | ------------------- |
    | Cloud Foundry                     | MEMORY      | 1                   |
    | SAP Build                         | User        | 1                   |
    | Destination                       | lite        | 1                   |
    | Cloud Identity Services           | application | 1                   |

3. Subscribe to the following applications:

Subscriptions required in your SAP Business Technology Platform Account:

| Subscription                      | Plan             |
| --------------------------------- | ---------------- |
| SAP Build Lobby                   | standard         |

4. Make sure that you have an instance of Cloud Identity Services assigned to your subaccount or create one.

5. Assign the following roles to your user:

    - BuildApps_Administrator
    - BuildApps_Developer

6. Enable Cloud Foundry.

7. Create a Cloud Foundry space.


