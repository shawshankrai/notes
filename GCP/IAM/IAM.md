# IAM

## Who can do What on Which resources

## Who - Identity

    * Google Account
    * Google Groups - Group of Accounts
    * Cloud Identity Account - Organization Accounts
    * Google Workspace Account - Organization Accounts, Will get google enterprise apps
    * Service Account

## What - Action

     * Create
     * Update
     * Delete

## Which – Resources

     * Compute Engine
     * App Engine
     * Cloud Storage

## Roles : Collections of Permissions

    * Built-in Roles
      * Primitive
        * Owner
        * Editor
        * Viewer
      * Pre-defined
        * Compute Admin
        * Storage Viewer
    * Custom Role
      * Combined collection of Permissions
    * Service Account
      * For apps
      * For services
      * Max 100 roles per service account
  
## Principals: The entities that can access GCP resources

    * Google Accounts.
    * Service accounts.
    * Google groups.
    * Google Workspace accounts.
    * Cloud Identity domains.
    * allAuthenticatedUsers.
    * allUsers.
    * One or more federated identities in a workforce identity pool.


## Is identity and principal same in GCP

    No, identity and principal are not the same in Google Cloud Platform (GCP), but they are related: 

        Identity
        An identity is a Google account, service account, Google group, Google Workspace account, Cloud Identity domain, or other entity that can access a GCP resource. 

        Principal
        A principal is an identity that has been granted access to a GCP resource. Principals can be assigned roles and bound to resources using Identity and Access Management (IAM) policies.
         
        Role
        A role is a collection of permissions that determine which operations can be used on a specific resource. 

        Policy
        A policy is a role constraint that binds a principal to a specific action for a resource. 
