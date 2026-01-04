## Task 2: Create groups and add members

In this task, you create a group account. Group accounts can include user accounts or devices. These are two basic ways members are assigned to groups: Statically and Dynamically. Static groups require administrators to add and remove members manually.  Dynamic groups update automatically based on the properties of a user account or device. For example, job title. 

1. In the Azure portal, search for and select `Microsoft Entra ID`. In the **Manage** blade, select **Groups**. 

1. Take a minute to familiarize yourself with the group settings in the left pane.

   + **Expiration** lets you configure a group lifetime in days. After that time the group must be renewed by the owner.
   + **Naming policy** lets you configure blocked words and add a prefix or suffix to group names.

1. In the **All groups** blade, select **+ New group** and create a new group.     

    | Setting | Value |
    | --- | --- |
    | Group type | **Security** |
    | Group name | `IT Lab Administrators` |
    | Group description | `Administrators that manage the IT lab` |
    | Membership type | **Assigned** |

    >**Note**: An Entra ID Premium P1 or P2 license is required for dynamic membership. If other **Membership types** are available, the options will show up in the drop-down. 
    
    ![Screenshot of create assigned group.](azure-lab01-create-assigned-group.png)

1. Select **No owners selected**.

1. In the **Add owners** page, search for and **select** yourself (shown in the top right corner) as the owner. Notice you can have more than one owner. 

1. Select **No members selected**.

1. In the **Add members** pane, search for and **select** the **az104-user1** and the **guest user** you invited. Add both of the users to the group. 

1. Select **Create** to deploy the group.

1. **Refresh** the page and ensure your group was created.

1. Select the new group and review the **Members** and **Owners** information.

>**Note:** You may be managing a large number of groups. Does your organization have a plan for creating groups and adding members?
