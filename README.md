# GoDaddy to  Microsoft 365 Tenant Migration

## Description
This project covers the execution of a live migration to move custom domains out of a GoDaddy-syndicated Office 365 environment and into a clean, native Microsoft 365 enterprise tenant. This was a complete, hands-on production deployment to break partner federation, extract the live domains, and move the domain over to the destination tenant.

## Language Used
* **PowerShell:** 

## Modules Used
* **Microsoft.Graph**
* **ExchangeOnlineManagement**

## Project Goals Achieved
* **Broke Partner Federation:** Successfully converted the source tenant from federated to managed, removing the GoDaddy administrative lock.
* **Purged Legacy Directory Anchors:** Cleared the source directory of all matching custom domain routing objects to prevent tenant collisions during the move.
* **Finalized Identity Cutover:** Registered and verified the custom domain on the destination tenant, successfully migrating the primary global administrator account to the native domain.
