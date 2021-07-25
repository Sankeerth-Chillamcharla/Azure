
![sankeerthchillamcharla (3)](https://user-images.githubusercontent.com/46291282/126900246-194b0ec4-1711-4010-9f13-165927576142.png)


# Problem Statements

  1. Create a Virtual network in West US and  create another Virtual Network in Central India, deploy the 2VM's in a different virtual networks. Create Vnet-Vnet Peering to connect West US and Central India VM, to check network peering connection use VM1 private IP address try to ping in VM2 CLI using ping command.

  2.  Create a virtual machine in the East US region, create a new public IP address and change private IP address status as static, and create a new NIC and attach to a current virtual machine, then create a new NSG and attach to a current virtual machine, and open the port number 80, install apache2 in the VM and  Verify we can access the apache landing page or not, then create azure DNS Service to map VM public IP to the domain name.
 


### 1. Create a Virtual network in West US and  create another Virtual Network in Central India, deploy the 2VM's in a different virtual networks. Create Vnet-Vnet Peering to connect West US and Central India VM, to check network peering connection use VM1 private IP address try to ping in VM2 CLI using ping command..

  **Step 1:** 
  
  ![image](https://user-images.githubusercontent.com/46291282/126879067-c0670719-b819-418a-bcc4-2e1c23010839.png)
  
  **Step 2:** 
  
  ![image](https://user-images.githubusercontent.com/46291282/126879072-f95ba016-f8d7-4ea4-8b50-91a67a42e339.png)
  
   **Step 3:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126879119-d3d98b4a-5684-463a-bf99-20aba9b1eb24.png)
   
   **Step 4:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126879127-86bb4dad-b639-4cd6-8f26-c66103a339fd.png)
   
   **Step 5:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126879143-6c0fdb43-0177-4b32-9f70-e807d3cd4c97.png)
   
   **Step 6:** Follow the Step 1 to Step 5 to create a another VNET in Centeral India Region.
   
   ![image](https://user-images.githubusercontent.com/46291282/126879158-e5c42725-7851-41d9-a77c-a93e7e257103.png)
   
   
   **Step 7:** To create a VM in different regions refer [https://github.com/Sankeerth-Chillamcharla/Azure/tree/main/Azure%20Virtual%20Machine](AVM). 
   
   **NOTE:** While creating the VM in NETWORKING TAB select the newely created **VNETS**. 
   
   ![image](https://user-images.githubusercontent.com/46291282/126879264-594283bd-9339-4c2d-8568-381dd2c24b3d.png)
   
   **Step 8:** 
   
   ![image](https://user-images.githubusercontent.com/46291282/126879278-643c419b-7ad7-4320-97f4-70c4f770d513.png)
   
   **Step 9:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126879298-722fdfd9-9395-4fc7-a8f9-7ff344c27fda.png)
   
   **Step 10:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126879309-a6e9ee5f-5e16-4a02-b5ee-ee4db76f5cbe.png)
   
   **Step 11:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126879328-7e44fdf1-64db-49a1-846d-f16205bd2554.png)
   
   **Step 12:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126879334-e6c09a1f-bd60-4e74-9344-de37fceea9bf.png)
   
   
 ### 2. Create a virtual machine in the East US region, create a new public IP address and change private IP address status as static, and create a new NIC and attach to a current virtual machine, then create a new NSG and attach to a current virtual machine, and open the port number 80, install apache2 in the VM and  Verify we can access the apache landing page or not, then create azure DNS Service to map VM public IP to the domain name.
 
   **Problem Statement Breackdown**
   
   - Create a new resource group in East us region
   - Create a VNET in same region
   - Create a Public IP address
   - Create a NIC (Network interface card)
   - Create a NSG ( Netork security  Group)
   - Create a Linux VM 
   - Create DNS in the same region.
   - Update the name servers and map vm public IP to DNS 

  
  **Step 1:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126907736-1af78da5-aa49-460c-9a6e-c808eec0453f.png)
  
  **Step 2:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126907765-20a2cdd3-7af6-4f6c-9093-4d3fb63d3be9.png)
  
  **Step 3:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126907828-06eb6b34-8ac9-44c9-9aa0-2c639ed4aa42.png)


  **Step 4:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126907809-58b8f5c4-25e2-4f43-86ba-ccdbc398b574.png)
  
  **Step 5:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126907884-d007e04c-ce09-4cbb-8c47-439a5f42fc69.png)
  
  **Step 6:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126907935-9ff23f09-eff3-494a-a71a-953939f9e978.png)

  **Step 7:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126907951-704c7d6a-cfa7-42cd-920d-d4323c27d827.png)

  **Step 8:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908002-bc63e7b6-0e42-4cb7-85c4-28973cb287b3.png)

  **Step 9:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908035-c6a0f149-42aa-43fc-8553-aadc589187e6.png)
  
  **Step 10:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908062-bf70fc80-767a-4af6-869f-9d174dc2130f.png)
  
  **Step 11:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908086-5e4ef438-51c7-4f21-aa45-44eee47d570c.png)
  
  **Step 12:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908095-872e0177-8616-4206-b0b6-963e7492dc72.png)
  
  **Step 13:**
 
  ![image](https://user-images.githubusercontent.com/46291282/126908146-d33cfe3a-89e6-49dc-9e19-87e4445ceb70.png)

  **Step 14:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908191-ad0a0ee2-0e96-444e-9e93-4cdd7d07fc92.png)

  **Step 15:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908212-895a40af-a561-4e2f-b191-2765b6fd8113.png)

  
  **Step 16:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908250-7ebebf48-ac25-4a40-aa04-90bbfa6064b4.png)

  **Step 17:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908314-54e07218-4966-4e65-8f6e-2fc5ed37abe8.png)
  
  **Step 18:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908347-99cdd461-7179-49de-9cb6-c531c425c5fd.png)

  **Step 19:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908380-b35aad41-5a5f-43e9-af14-be7feff0aea2.png)

  **Step 20:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908422-8a3e5fca-7630-4091-bbdb-f87e77d1511c.png)

  **Step 21:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908446-a15cce69-84d7-49fb-8539-413237d13132.png)

  **Step 22:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908496-711a1247-d3e6-4b6a-bf09-7a4de6fbea84.png)

  **Step 23:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908521-0407266b-3b32-4ea3-b41f-33e2dac8f720.png)

  **Step 24:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908584-1bde5b6a-5a39-4ecb-9f22-1b97c3873ab1.png)

  **Step 25:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908638-e3b372a9-6642-4e97-971d-b2f47ab11257.png)

  **Step 26:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908656-536dc469-8c9b-4152-bbaf-5c95141b8145.png)

  **Step 27:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908724-01e9b51c-3d27-42ab-83ce-5715718d905c.png)

  
  **Step 28:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908742-9e9031d4-74fe-4d51-935f-d528f1978682.png)

  **Step 29:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126908772-0291b2eb-d834-4fb0-ba13-de730fdbfcae.png)

  **Step 30:**
  
     sudo apt-get update
     sudo apt-get install  apache2 -y
  
  ![image](https://user-images.githubusercontent.com/46291282/126909226-2709d968-7024-48d3-91ec-b636dec91cb6.png)
  
  ![image](https://user-images.githubusercontent.com/46291282/126909256-da0dbf6d-450f-4f13-9277-9453fcd1b43b.png)

  **Step 31:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126909290-20a4fdd9-ddb4-486d-b8a2-4133008ee27c.png)

  
  **Step 32:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126909349-ca9857b8-5fff-41ed-acc2-187565030712.png)

  
  **Step 33:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126909363-e44fba08-89ac-41a1-b785-3cc523eb7390.png)

  
  **Step 34:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126909393-b611cb8f-a225-43ca-bb1c-51616e35e4d7.png)

  
  **Step 35:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126909422-ac975236-eae2-48ca-bf13-3e6ccc5ae03d.png)

 
  **Step 36:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126909477-30817f88-81bd-48d5-ada5-652553b06e32.png)

  
  **Step 37:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126909494-7aa97238-715f-4304-81c6-2beebebf0bd9.png)
  
  
  **Step 38:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126909514-3525f91e-0d21-427c-b991-a34773e02333.png)
  
  **Step 39:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126909611-72c5833c-8ad5-4a10-b0e8-54675f33cb3f.png)


  
  

  
  



 
 
 

   
   
   

   


   
   
   
   
   

   
   
   

                  
  


   
   
   

   
   




