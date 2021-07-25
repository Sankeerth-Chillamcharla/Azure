
![sankeerthchillamcharla (3)](https://user-images.githubusercontent.com/46291282/126900246-194b0ec4-1711-4010-9f13-165927576142.png)


# Problem Statements

  1. Create a Virtual network in West US and  create another Virtual Network in Central India, deploy the 2VM's in a different virtual networks. Create Vnet-Vnet Peering to connect West US and Central India VM, to check network peering connection use VM1 private IP address try to ping in VM2 CLI using ping command.

  2.  Create a virtual machine in the West US region, create a new public IP address and change private IP address status as static, and create a new NIC and attach to a current virtual machine, then create a new NSG and attach to a current virtual machine, and open the port number 80, install apache2 in the VM and  Verify we can access the apache landing page or not, then create azure DNS Service to map VM public IP to the domain name.
 


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
   
   
 ### 2. Create a virtual machine in the West US region, create a new public IP address and change private IP address status as static, and create a new NIC and attach to a current virtual machine, then create a new NSG and attach to a current virtual machine, and open the port number 80, install apache2 in the VM and  Verify we can access the apache landing page or not, then create azure DNS Service to map VM public IP to the domain name.
 
   **Problem Statement Breackdown**
   
   - Create a new resource group in west us region
   - Create a VNET in same region
   - Create a Public IP address
   - Create a NIC (Network interface card)
   - Create a NSG ( Netork security  Group)
   - Create a Linux VM 
   - Create DNS in the same region.
   - Update the name servers and map vm public IP to DNS 
 
 
 

   
   
   

   


   
   
   
   
   

   
   
   

                  
  


   
   
   

   
   




