
![sankeerthchillamcharla (4)](https://user-images.githubusercontent.com/46291282/127182415-f8701f0a-63fa-416f-b200-afb8297e1b47.png)


# Authentication And Authorization In Azure & Azure Active Directory

# Problem Statement

  1. Create a custom role which can view, start and stop VMs.
  2. Create a new user and assign previous role.
  3. Create a user group and assign the previous role and check whether the permissions get assigned or not.



# 1. Create a custom role which can view, start and stop VMs

  **Step 1:** Refer [Custom Role Template](https://docs.microsoft.com/en-us/azure/role-based-access-control/tutorial-custom-role-cli#create-a-custom-role)  and copy the custom role example JSON template and create a JSON file with this code. Name this file as new_role.json.
  
  ```javascript
  {
    "Name": "",
    "IsCustom": true,
    "Description": "",
    "Actions": [],
    "NotActions": [],
    "DataActions": [],
    "NotDataActions": [],
    "AssignableScopes": [
      "/subscriptions/{subscriptionId1}"
    ]
  }
  ```
  
  **Step 2:**  Add Name and description of role in new_role.json file  
  
  ```javascript
  {
    "Name": "Virtual Machine Operator",
    "IsCustom": true,
    "Description": "Can monitor and restart virtual machine",
    "Actions": [],
    "NotActions": [],
    "DataActions": [],
    "NotDataActions": [],
    "AssignableScopes": [
      "/subscriptions/{subscriptionId1}"
    ]
  }
  ```
  
   **Step 3:**  For actions refer [Azure resource provider operations](https://docs.microsoft.com/en-us/azure/role-based-access-control/resource-provider-operations#compute).
   
  ```javascript
  {
    "Name": "Virtual Machine Operator",
    "IsCustom": true,
    "Description": "Can monitor and restart virtual machine",
    "Actions": ["Microsoft.Storage/*/read",
                "Microsoft.Network/*/read",
                "Microsoft.Compute/*/read",
                "Microsoft.Compute/virtualMachines/start/action",
                "Microsoft.Compute/virtualMachines/restart/action",
                "Microsoft.Authorization/*/read",
                "Microsoft.ResourceHealth/availab
                ],
    "NotActions": [],
    "DataActions": [],
    "NotDataActions": [],
    "AssignableScopes": [
      "/subscriptions/{subscriptionId1}"
    ]
  }
  ```
  
  **Step 4:** Now Add scuscription id in new_role.json.
  
      Get-AzSubscription
  
  ![image](https://user-images.githubusercontent.com/46291282/127186441-9b675d31-4106-484b-ba08-ffedc5a7ae02.png)
  
   ```javascript
  {
    "Name": "Virtual Machine Operator",
    "IsCustom": true,
    "Description": "Can monitor and restart virtual machine",
    "Actions": ["Microsoft.Storage/*/read",
                "Microsoft.Network/*/read",
                "Microsoft.Compute/*/read",
                "Microsoft.Compute/virtualMachines/start/action",
                "Microsoft.Compute/virtualMachines/restart/action",
                "Microsoft.Authorization/*/read",
                "Microsoft.ResourceHealth/availab
                ],
    "NotActions": [],
    "DataActions": [],
    "NotDataActions": [],
    "AssignableScopes": [
      "/subscriptions/{subscriptionId1}"
    ]
  }
  ```

  

