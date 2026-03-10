# Project 3 — Azure Role-Based Access Control (RBAC)

## Skills Demonstrated

- Microsoft Entra ID user management
- Azure Role-Based Access Control (RBAC)
- Least privilege access model
- Resource group permission assignment

## Architecture

Azure Subscription
│
├─ Resource Group
│
├─ Storage Account
│
└─ RBAC
     └─ Reader role assigned to user

## Steps Performed

1. Created a new Microsoft Entra ID user.
2. Navigated to the resource group.
3. Opened Access Control (IAM).
4. Assigned the Reader role to the test user.
5. Verified role assignment in IAM.

## Security Concept

This project demonstrates implementing least privilege access by assigning read-only permissions to a user at the resource group scope.

## Result

The user can view resources but cannot create, modify, or delete them.
