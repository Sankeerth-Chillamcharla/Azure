# Azure Storage


## Problem Statement 1 

### Create 2 resource groups rg-1 and rg-2,  add storage account to rg-1 and move storage account from rg-1 to rg-2

#### Step  1.1

Signin (or) signup to the azure portal. 

#### Step 1.2 

Article about how create [Resourcs Groups](https://github.com/Sankeerth-Chillamcharla/Azure/blob/bbeb34041af7f83c54136e01965d3dedee662aed/Resource%20Group/Readme.md) in Azure. 

![image](https://user-images.githubusercontent.com/46291282/123836140-fb1e8c80-d926-11eb-9bc9-db753aae2b7a.png)

#### Step 1.3

###### Step 1.3.1  Using the serch bar in the top navigation, serch with keyword **Storage Account** then click on the storage account.

![image](https://user-images.githubusercontent.com/46291282/123837580-a714a780-d928-11eb-91c5-4a102259215f.png)


###### Step 1.3.2

we are creating the storage account with deafult options provided by the Microsoft azure.

1. Select the active subscruption group.
2. Select rg-1 resource group
3. Enter a new storage account name
4. Select the required region
5. Select performance as standard option
6. Select redundancy as a **LRS**
7. Now click on the **Review + Create** button.


![image](https://user-images.githubusercontent.com/46291282/123838997-3ec6c580-d92a-11eb-9aeb-be5bc11ee5da.png)

Once validation is passed click on the **Create** option, it will take few secound to creat storage account. 

![image](https://user-images.githubusercontent.com/46291282/123839017-45553d00-d92a-11eb-8962-b35b7054df3b.png)


Now go to the **rg-1** resource group, where we can able to see the new storage account **rgstroagedemo1**.

![image](https://user-images.githubusercontent.com/46291282/123839156-6ddd3700-d92a-11eb-962e-dd57dedca93f.png)


#### Step 1.4

###### Step 1.4.1 

Go to your your  [Resourcs Groups](https://github.com/Sankeerth-Chillamcharla/Azure/blob/bbeb34041af7f83c54136e01965d3dedee662aed/Resource%20Group/Readme.md) and click on the **rg-1** resource group name. After click, a new side window will be opened. Now click on the **Move to another resourcegroup**, it will redirect to the move resources section.

![image](https://user-images.githubusercontent.com/46291282/123840354-d7aa1080-d92b-11eb-8cb9-98e0230e11bc.png)

###### Step 1.4.2 

Now select storage account and new resource group then click on **OK**, it will take few minutes to transfer sotrage acount form rg-1 resource group to rg-2 resource group.

![image](https://user-images.githubusercontent.com/46291282/123841386-1c827700-d92d-11eb-8eed-3e5e0f3ce947.png)


## Problem Statement 2 

###   Create 3 storage accounts with “Team” tags: team1, team2 and team3 respectively.
###   Create one more storage account for team2 and list all resources for team2 using tags

#### Step  2.1
Signin (or) signup to the azure portal. 

#### Step 2.2

Follow the problem statement 1 solution for the storage account creation but before click on the **Review + Create** button, 
go the **Tags tab** Tags tab and enter the name and value.

![image](https://user-images.githubusercontent.com/46291282/123843047-12fa0e80-d92f-11eb-8eaf-0014e39f9b90.png)

Follow the same steps to 4 storage accounts in **rg-1** resource group with the different tags. 

![image](https://user-images.githubusercontent.com/46291282/123844016-235eb900-d930-11eb-8d9a-a97db7800a95.png)

#### Step 2.3

Click on the add filter option and select the tag keyword as **team2** and click on apply. 

![image](https://user-images.githubusercontent.com/46291282/123844271-6e78cc00-d930-11eb-83fe-b493845b5a2b.png)

 Now we can able to access storage which are having **team2** keyword.
 
 ![image](https://user-images.githubusercontent.com/46291282/123845217-8bfa6580-d931-11eb-9d06-53a7782008ed.png)


## Problem Statement 3 

###  Create a File share in Azure Storage.
###  Mount this file share on windows.

#### Step 3.1 

Click on the **rgteam1** storage account name and it will redirect to the storage account section. 
Go to left navigation **Data Storage** section and click on the **File Share** button it will redirest to the file share section.

![image](https://user-images.githubusercontent.com/46291282/123891238-3e541c00-d976-11eb-9cbc-51a5b7bbba95.png)

#### Step 3.2

Click on the **+FIleshare** button the right side new **New file share** model will open. 

![image](https://user-images.githubusercontent.com/46291282/123891634-d3571500-d976-11eb-81f4-fa1b82e24142.png)

#### Step 3.3

---> Enter a new storage account name and storage limit.
---> Select the require tire and click on **create** button it will take few secound to create a **Files Share** 

![image](https://user-images.githubusercontent.com/46291282/123892212-c686f100-d977-11eb-9efd-fb27fab78369.png)

#### Step 3.4 

Now click on the **rgdevstorage** it will redirect to the file share section. 

![image](https://user-images.githubusercontent.com/46291282/123892422-2d0c0f00-d978-11eb-9c41-e4eb84fb734c.png)


#### Step 3.5 

Go to tab navigation section and click on the **connect**, then select your drive letter and OS type on bottom section connecting script will generate.

![image](https://user-images.githubusercontent.com/46291282/123892726-c0454480-d978-11eb-8b85-fef6622093a0.png)

Copy the script and open powershell in your local system and run it it will automatically add new network .




