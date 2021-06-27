![image](https://user-images.githubusercontent.com/46291282/123545171-5fe5b580-d774-11eb-9b8f-5597625b7b81.png)

# How to Ceate Resource Grops in Azure?

## Introduction

A resource group is a logically container that holds related resources like virtual machines, storage accounts, virtual networks, 
web apps, databases, and/or database servers  for an Azure solution. 

      
### Ways to Create an Azure Resource Group
- Azure Portal
- Azure PowerShell
- Azure CLI
- An ARM template

## Prerequisite

      1.Azure Cloud Account with active subscription
      2.Stable Internet Connection
      3.Edge (or) any other internet browsers

#  Create resource groups by using Azure Portal

### Step 1 
Signin (or) signup to the azure portal.

### Step 2   
Select the Resource Group form the left top navigation bar and click on **Create** button.  
![image](https://user-images.githubusercontent.com/46291282/123547761-a68cdd00-d77f-11eb-9e90-d650a1b817fc.png)


### Step 3 
1. Select the active subscruption group.
2. Enter a new resource group name.
3. Select the required region
4. click on Next button.

![image](https://user-images.githubusercontent.com/46291282/123547773-b1e00880-d77f-11eb-923e-bc8c2b957b07.png)

### Step 4 
Enter the **Tag Name** and **Value** after that click on the **Review + Create** button it will redirect to vlaidation section.

![image](https://user-images.githubusercontent.com/46291282/123547786-bad0da00-d77f-11eb-8c34-e3dd4bce65df.png)


### Step 5 

1.After click on **Review + Create** it will redirect to the validation and we can see the validation success message. Now click on the **Create button**. 
It will take few secounds to create a resource group. 

![image](https://user-images.githubusercontent.com/46291282/123547797-c8865f80-d77f-11eb-9fa6-be1b7a3ada32.png)

2. Select the Notification (bell icon) on the right top navigation.

![image](https://user-images.githubusercontent.com/46291282/123547806-d20fc780-d77f-11eb-8611-84d6777f1ccc.png)

3. Click on the Go to resource group, it will redirect to List of resource group page. 

![image](https://user-images.githubusercontent.com/46291282/123547811-d89e3f00-d77f-11eb-9740-43a25c567ee0.png)

 

#### Problme Statment 1   
1. Connect to Azure Cloud Shell
2. Create a resource group “new-rg” in South Central US region
      
#### Problme Statment 2    
1. Connect Azure powershell to your azure account
2. Create a new resource group in South Central US with the name “rg-powershell”

#### Problme Statment 3    
1. Create three more Resource groups in a specific region let’s say “West US”
2. List all resource groups in West US
      
 #### Problme Statment 4    
1. Delete all the resource groups in West US region using one command
