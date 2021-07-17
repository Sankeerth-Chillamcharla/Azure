# Azure Storage Part - II

![sankeerthchillamcharla](https://user-images.githubusercontent.com/46291282/126025220-8bc19d89-877c-4fe5-86c9-ac4a8a951855.png)

# Problem Statemts 
  
  1. Create a storage account and Connect storage account to azure storage explorer.
  2. Create a Fileshare using the Storage explorer.
  3. Upload files to the blob service
  4. Create an Azure Table and insert a record
  5. Create two storage account and create a container inside it and Upload some data to the first Blob service and using Data Factory copy data to the second storage service’s container


## 1. Create a storage account and Connect storage explorer to this storage account.

   **Step 1:** For creating storage account, refer [Storage Part - I](https://github.com/Sankeerth-Chillamcharla/Azure/blob/main/Storage/Readme.md) section.
   
   **Step 2 :** Go to Storage account, in **security + Networking** section click on the **access key**
   

   ![image](https://user-images.githubusercontent.com/46291282/126025869-622e4bff-cd2a-46a9-ad44-055d29b4b97e.png)
   
   
   **Step 3 :** Now click on the **SHOW KEYS**  and copy the **KEY1**
   
   
   ![image](https://user-images.githubusercontent.com/46291282/126025921-d67ffbfe-db09-40b0-8c2f-a8890661b76c.png)
   
   
   **Step 4 :** Downlaod the [azure storage explorer](https://azure.microsoft.com/en-us/features/storage-explorer/) and install in your local machines. Then click on windows start menu and open azure storage explorer
   
   
   ![image](https://user-images.githubusercontent.com/46291282/126026013-14cc8762-f605-4b24-988a-22a358422978.png)
   

   **Step 5 :** Now click on the **plug** icon form the side navigation, then copnnect azure storage account popout will open, in that select the **Storage account and services **
   
   ![image](https://user-images.githubusercontent.com/46291282/126026177-31619c56-9ea6-4311-9f5d-3cc401fd5c88.png)
   
   **Step 6 :** Select account **Name and Key** and click on the **Next** button. 
   
   ![image](https://user-images.githubusercontent.com/46291282/126026258-8c303b3b-22c5-4015-ac7b-cd158f72f0e1.png)
   
   **Step 7 :** Enter the Account name and access key and click next.
   
   ![image](https://user-images.githubusercontent.com/46291282/126026355-68f27058-f2e3-4cb0-aa37-3697c8ca3612.png)
   
   **Step 8 :** Fianl step ckick on the **CONNECT**.
   
   ![image](https://user-images.githubusercontent.com/46291282/126026411-7026e653-41f2-462e-93a3-3c615256deed.png)
   
   **Step 9 :**  Now the azure storage account is connected to the azure storage explorer.
   
   ![image](https://user-images.githubusercontent.com/46291282/126026453-6b65788d-6426-445a-9382-bc62f3b6b479.png)

## 2. Create a Fileshare using the Storage explorer.

   **Step 1:** Click on File share icon and again clikc on the create file share. 
   
   ![image](https://user-images.githubusercontent.com/46291282/126026621-c699acf7-afd2-4f26-a260-24f3598cbef5.png)
   
   **Step 2:** Click on the **Connect VM** and copy the code.
   
   ![image](https://user-images.githubusercontent.com/46291282/126026671-dd197ab6-5e7c-4c7e-bb9f-d50eafa41886.png)
   
   **Step 3:** Open CMD and Run the copied code. 
   
   ![image](https://user-images.githubusercontent.com/46291282/126028977-81a4f8cf-190f-432f-a3c1-0017772a2aa5.png)
   
   ![image](https://user-images.githubusercontent.com/46291282/126029005-6d681424-8dad-45bd-8337-381db9c7988a.png)

## 3. Upload files to the blob service.

   **Step 1:** Click on **Blob Continer** and again clikc on the **Create Blob Container**. 
 
  ![image](https://user-images.githubusercontent.com/46291282/126029095-56e5e8d0-bb17-4e7a-9732-405a085b95d8.png)

  **Step 2:** Now click on the upload icon and select the file and upload it to the blob storage. 

  ![image](https://user-images.githubusercontent.com/46291282/126029233-e10128b9-28e9-4ffe-ac59-b37bee103f92.png)

  **Step 3:** Once click on upload it will take few seconds to upload selected file in the blob storage. 

  ![image](https://user-images.githubusercontent.com/46291282/126029295-6a54433c-d87a-4889-971e-dd4df70f767c.png) 

  ![image](https://user-images.githubusercontent.com/46291282/126029317-ac23925a-dd44-4e41-a074-a15e1e31533d.png)

## 4. Create an Azure Table and insert a records.
  
   **Step 1:** Click on **Tables** and again clikc on the **Create Table**. 
   
   ![image](https://user-images.githubusercontent.com/46291282/126029510-d31387bf-11aa-4ffa-8b58-c3773e672231.png)
   
   **Step 2:** Click on **Add icon** and add entity window will open, in that click on the **add Property**, Now define property names and values and cick on **incert**.
   
   ![image](https://user-images.githubusercontent.com/46291282/126029645-b132e150-ec90-4236-b87c-5e9aa6bfaad0.png)
   
   ![image](https://user-images.githubusercontent.com/46291282/126029693-9947de57-3685-4653-aee6-debd0968182d.png)

## 4. Create two storage account and create a container inside it and Upload some data to the first Blob service and using Data Factory copy data to the second storage service’s container.
 
  **Step 1:** For creating the storage caontainer follow the above steps. 
  
  ![image](https://user-images.githubusercontent.com/46291282/126029743-bcd8620d-03d9-4ff3-805f-68ed08c8f2e0.png)
  
  ![image](https://user-images.githubusercontent.com/46291282/126029762-b10a28b4-74b7-4ca9-8899-80ac91684268.png)
  
  **Step 2:** Click on the datafactory and create the new data factory.
  
  ![image](https://user-images.githubusercontent.com/46291282/126029821-011d8d90-73d1-4635-80b6-2a75ac67b960.png)
  
  ![image](https://user-images.githubusercontent.com/46291282/126029855-f23159f2-7137-4f49-afa4-eda07c5be1ac.png)
  
  **Step 3:**  once new data factory account created, click on the **Azure Data Factory studio** it will redirect to the azure data factory and click on the **Transform data**.
  
  ![image](https://user-images.githubusercontent.com/46291282/126029972-65458055-e093-4c95-87dc-4930280fa8c0.png)
  
  ![image](https://user-images.githubusercontent.com/46291282/126030016-2f5aac2d-41a1-46c7-83b7-5dce044121ba.png)

   **Step 4:**  
  

  
  
  
  



  


  
  
   
   

   


 
 


   
   
   

   
  

   



   
   



