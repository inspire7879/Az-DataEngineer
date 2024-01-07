## Azure Service Principal

## Verifying App Registration Permision
> Portal -> Active Directory -> Users -> Click on the User -> Check App Registration Switch

### Create New 
> Portal -> App Registration -> Register an application
- user id and password as called as app id, secret
- Application (client) Id present in the overview page of Newly Registered App will be used by the apps.
- Create Secret
  > Portal -> App Registration  -> Click on Newly registered App -> Click Certicates & secret
  - Value is the one used by the apps
  
## Password Rotation
- Create a new password before the old password expired with same Secret Id.
- Stop the application and restar
- Delete the expired Secret
- Restart App

## Azure Hierarchy 
AAD 
 > multiple subscription
   > 1 subscription multiple resource groups
     - 1 RG can contain multiple resource
 > 
