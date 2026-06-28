# Lab 01 – Manage Microsoft Entra ID Identities

## Overview
Provisioned user accounts and groups in Microsoft Entra ID to support 
a simulated pre-production environment. Configured both static and 
dynamic group membership.

## Skills Demonstrated
- Creating and configuring cloud user accounts in Entra ID
- B2B guest user invitation
- Static vs dynamic group membership (requires P1/P2 license)
- Understanding tenant structure in Azure

## Tasks Completed
1. Created user account `az104-user1` with department and job title attributes
2. Invited an external guest user via B2B collaboration
3. Created a security group with static membership
4. Configured dynamic membership rule based on job title

## Key Takeaways
- Dynamic groups update automatically based on user attributes, 
  reducing admin overhead at scale
- Entra ID is the identity backbone for all Azure RBAC and resource access
- Guest access enables cross-org collaboration without separate accounts

## Screenshots
See the `/Screenshots` folder for evidence of completed tasks.

## Lab Reference
[Microsoft Learn – AZ-104 Lab 01](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_01-Manage_Entra_ID_Identities.html)
