# Class 8: Access Control


## 5 Steps to RBAC

1. What is Role Based Access Control (RBAC) and why do we care?

    * RBAC is the assignment of system access to the users based upon their role within an organization.

2. Describe a Role/Permission heirarchy that you might implement using RBAC.

    * For example; You could assign super user privilages to a system admin that needs to administer the network, while giving read-only access to someone like a customer service agent that only needs to see customer data.

3. What approach might you take to implement RBAC?

    1. Inventory your systems
    2. Analyze your workforce and create roles
    3. Assign people to roles
    4. Never make one-off changes
    5. **Audit**

    Source: [CSO Online](https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html)

## Wiki - RBAC

1. If Authentication is “you are who you say you are,” what is Authorization?

    * Authorization would be "what you're allowed to do."

2. Name three primary rules defined for RBAC.

    1. Role Assignment:  
        * A subject can exercise a permission only if the subject has selected or been assigned a role.
    2.  Role Authorization:
        *  A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.
    3. Permission Authorization:
        *  A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.

3. Describe RBAC to a non-technical friend.

    * Essentially, access to privilages is restricted based upon your role and what you do in an organization.

## RBAC Tutorial

1. What Are access rights Associated with? The User? or The Role? Explain.

    * Access rights are associated with a role.  A user's role determines what rights they can access and what they can do in the system.

2. Access Rights, or Authorization, is activated after a user successfully does what?

    * After a user logs in and is assigned a role.

3. Explain how RBAC might benefit a business.

    * It limits the security risk that each employee and system represents, and it potentially contains the damage that can be done to the system.
    * It makes maintenance of the policy and authorization list easier.

[Return to Table of Contents](https://haydencleaver.github.io/reading-notes/)