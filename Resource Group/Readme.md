![image](https://user-images.githubusercontent.com/46291282/123545171-5fe5b580-d774-11eb-9b8f-5597625b7b81.png)

# How to Create Resource Groups in Azure?

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
1. Select the active subscription group.
2. Enter a new resource group name.
3. Select the required region
4. click on Next button.

![image](https://user-images.githubusercontent.com/46291282/123547773-b1e00880-d77f-11eb-923e-bc8c2b957b07.png)

### Step 4 
Enter the **Tag Name** and **Value** after that click on the **Review + Create** button.

![image](https://user-images.githubusercontent.com/46291282/123547786-bad0da00-d77f-11eb-8c34-e3dd4bce65df.png)


### Step 5 

1.After click on **Review + Create** button it will redirect to the validation section and we can see the validation success message and  click on the **Create button**. 
It will take few seconds to create a resource group. 

![image](https://user-images.githubusercontent.com/46291282/123547797-c8865f80-d77f-11eb-9fa6-be1b7a3ada32.png)

2. Select the Notification (bell icon) on the right top navigation.

![image](https://user-images.githubusercontent.com/46291282/123547806-d20fc780-d77f-11eb-8611-84d6777f1ccc.png)

3. Click on the Go to resource group, it will redirect to List of resource group page. 

![image](https://user-images.githubusercontent.com/46291282/123547811-d89e3f00-d77f-11eb-9740-43a25c567ee0.png)

 

#### Problem Statement 1 


 

1.1 **Connect to Azure Cloud Shell**

##### Step 1 
Signin (or) signup to the azure portal. 

##### Step 2

Click on the **Cloud Shell** icon available in the right top navigation and click on power shell button. 

![ps1](https://user-images.githubusercontent.com/46291282/123557391-44979c00-d7ae-11eb-80ac-a8af51515128.png)

##### Step 3 
Manually select **subscription** and Click on the **creatre storage**. It will take few seconds to c a storage account, after creating the 
storage account automatically Azure Cloud shell will open. 

![ps1 1](https://user-images.githubusercontent.com/46291282/123557396-4d886d80-d7ae-11eb-956d-3ec4141ce6a7.png)


1.2. **Create a resource group “new-rg” in South Central US region**

            PS> New-AzResourceGroup -Name new-rg -Location "South Central US"

![image](https://user-images.githubusercontent.com/46291282/123557500-b7a11280-d7ae-11eb-9951-12fd6e0c07df.png)

      
####  Problem Statement 2 
    

2.1. **Connect Azure Power shell to your azure account**

Open Power Shell application on local windows system and r the below command then automatically it will redirect to the azure login page.

            az login

![image](https://user-images.githubusercontent.com/46291282/123557480-9c360780-d7ae-11eb-9bbf-5c94b6cab633.png)


      
2.2. **Create a new resource group in Central US with the name “rg-powershell”**

Run the following in **Azure Power shell** to create resource group.

            az group create --location centralus --name rg-powershel

![ps2](https://user-images.githubusercontent.com/46291282/123557353-1ca83880-d7ae-11eb-9963-ecd5a90e9c78.png)


#### Problem Statement 3 
 
3.1. **Create three more Resource groups in a specific region let’s say “West US”** 

R the below command in the **Azure C**

      for i in 1 2 3; 
      do  az group create --location westus --name rg-wus-$i; 
      echo "Sucessfully New Resource Group rg-wus-$i created" ; 
      done

![ps3 1](https://user-images.githubusercontent.com/46291282/123557312-e074d800-d7ad-11eb-966d-47eddfcc9786.png)

3.2. **List all resource groups in West US** 

R the following command in **Azure Power shell** to fetch the all 
resource groups form the **West US** location


            Get-AzureRmResourceGroup -location westus

![ps4](https://user-images.githubusercontent.com/46291282/123557288-b15e6680-d7ad-11eb-9a5e-f3cd6c1c3d15.png)


 #### Problem Statement 4
  
4.1. **Delete all the resource groups in West US region using one command**

  R the following command in **Azure Power shell** to Delete the all resource groups ion the West Us location

       Get-AzureRmResourceGroup -location westus | Remove-AzureRmResourceGroup -Verbose -Force

![ps4](https://user-images.githubusercontent.com/46291282/123557255-82e08b80-d7ad-11eb-9d39-5fd9244d2e8d.png)

