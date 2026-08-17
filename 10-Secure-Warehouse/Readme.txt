Secure a Microsoft Fabric data warehouse
Microsoft Fabric permissions and granular SQL permissions work together to govern Warehouse access and user permissions. In this exercise, you’ll secure data using granular permissions, column-level security, row-level security, and dynamic data masking.

For this exercise, you will need two Fabric accounts: 
fabric1-regular account
fabric2-regular account with view access from the fabric1 workspace

In the workspace of the fabric1 account: manage access -->add the user-->add the fabric2 account and give viewer access only.


In this hands-on, you'll be experiencing the following things


1. Create a workspace
2. Create a data warehouse
3. Apply dynamic data masking rules to columns in a table
4. Apply row-level security
5. Implement column-level security
6. Configure SQL granular permissions using T-SQL


