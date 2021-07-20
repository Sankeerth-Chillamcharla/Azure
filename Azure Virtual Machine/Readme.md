
![sankeerthchillamcharla (2)](https://user-images.githubusercontent.com/46291282/126346132-402e0e34-6b65-4c24-875f-c9b19682d8a4.png)

# Azure Virtual Machine

# Problem Statement
  1. Create a VM (Ubuntu)  in the West US region and Open the SSH port, connect to the VM using the terminal.
  2. Create a Windows VM in West US region and Open the RDP port. Connect to it using Windows Remote Desktop.
  3. Create a VM (Ubuntu) scaleset and give min VM’s as 1, and maximum as 5, for Scaleout CPU utilization is 75% , and increase by 1 VM and scale in CPU utilization is 25% by 1VM.
  4. Create a Linux VM with ubuntu OS nad install apache2 software and create a image out of VM.
  5. Deploy a VM from the previously created image, open Port 80 in NSG, Start the apache2 service in the VM, and Verify if you are able to access the website.


## 1. Create a VM (Ubuntu)  in the West US region and Open the SSH port, connect to the VM using the terminal.

  
   **Step 1:**  
   
   ![image](https://user-images.githubusercontent.com/46291282/126190769-4d85596d-38f6-429d-8576-64921260e952.png)
   
   **Step 2:**  
   
   ![image](https://user-images.githubusercontent.com/46291282/126191120-aa2566bd-84d6-4f21-8e7f-93cd3af2af40.png)
   
   **Step 3:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126191412-5f9c052e-23c2-4671-96af-20c85916c557.png)
   
   **Step 4:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126191559-f072f7f2-e31e-4100-8980-e1a73f1d79b1.png)
   
   **Step 5:**
  
   ![image](https://user-images.githubusercontent.com/46291282/126191699-7de0867f-cc32-4966-95a4-5a0df8024aec.png)
   
   **Step 6:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126192046-7b468321-3f75-4115-b27b-d69dce87490a.png)
   
   **Step 7:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126193058-0c99d4d0-67e3-48c1-8a6c-4f5271dd068a.png)


## 2. Create a VM (Ubuntu)  in the West US region and Open the SSH port, connect to the VM using the terminal.

   **Step 1:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126198096-41b75533-fe3c-4075-8f25-e389b85e3896.png)

   **Step 2:**
   
  ![image](https://user-images.githubusercontent.com/46291282/126198628-797a1059-092c-4dcc-b20b-41415bdf36e5.png)
  
   **Step 3:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126198691-22793ac1-d29d-4dec-800c-a514c96ce7db.png)
   
   **Step 4:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126198770-3f6732af-54e4-4a50-8928-c32b12df499f.png)
   
   **Step 5:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126198804-a7af7286-7d29-42cf-8c40-dedbe8dfd52e.png)
   
   **Step 6:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126198861-219fb05b-eddd-475d-b936-821ff66502d6.png)
   
   **Step 7:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126198904-1d50ea3e-5898-4d74-a205-4232da41f891.png)
   
   **Step 8:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126198950-fd675a35-f846-44ef-a450-816e79cb7d71.png)
   
 
 ## 3. Create a VM (Ubuntu) scaleset and give min VM’s as 1, and maximum as 5, for Scaleout CPU utilization is 75% , and increase by 1 VM and scale in CPU utilization is 25% by 1VM.
 
  **Step 1:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126200119-caf0fe28-3654-49ee-93e4-2e070c99d806.png)
  
  **Step 2:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126200233-709e87bb-9ef6-40a3-9c98-1c703ae95d7a.png)
  
  **Step 3:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126200309-b05e32d7-297d-4689-9e61-a9b44a454b07.png)
  
  **Step 4:**
  
  ![image](https://user-images.githubusercontent.com/46291282/126200374-63bd0120-d058-4424-befd-bc3bc2460d50.png)
  
   **Step 5:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126200440-e1dbfd11-de8c-4749-a5eb-8fd6c4f1456d.png)
   
   **Step 6:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126200815-da96f807-262c-4a29-9d5c-17eb1fccd8bf.png)
   
   
## 4. Create a Linux VM with ubuntu OS nad install apache2 software and create a image out of VM.

   **Step 1:** Refer the Solution 1 for creating the and connection Linux VM. 
   
   **Step 2:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126203513-6397621c-5ce6-4c52-a5b2-819f33d5af02.png)
   
      1  sudo apt-get update
      2  sudo apt-get install apache2
      
   **Step 3:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126203641-7db3f4f2-e823-43ff-906d-5222a6b492d7.png)
   
   **Step 4:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126204168-9c698a98-2358-4da5-89d1-745b7ca716c7.png)
   
   
   **Step 5:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126204230-c46d3a3e-582d-4b68-9da8-f87db35f5012.png)
   
   
   **Step 5:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126204276-1242ec38-b4e8-4b30-928e-c686d5dfcdde.png)
   
   **Step 6:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126206503-21bd2ed5-8be7-4699-a767-8fc5e4eca3b7.png)
   


## 5. Deploy a VM from the previously created image, open Port 80 in NSG, Start the apache2 service in the VM, and Verify if you are able to access the website.
    
   **Step 1:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126344501-d1563f05-ce0d-49f7-9218-f354a802cd5c.png)
   
   **Step 2:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126344717-a3356b82-c50a-4dfe-b833-cb7b2b77fb7c.png)
   
   **Step 3:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126344847-9204990e-2f99-43d4-88f1-610e8b780a2f.png)
   
   ![image](https://user-images.githubusercontent.com/46291282/126344963-945dc6b9-4ec9-4de4-851f-3f821ba90937.png)
   
   ![image](https://user-images.githubusercontent.com/46291282/126345059-a7ef27b4-8a8b-4e62-951f-db0c45785754.png)

   **Step 4:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126345225-4bd67564-058b-4b88-a189-be8a2468c401.png)
   
   **Step 5:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126345302-d1ae211f-cde4-456d-89de-65559474c49b.png)
   
   **Step 6:**
   
   ![image](https://user-images.githubusercontent.com/46291282/126345388-955b87e8-4661-4e32-99e8-b0bcb562e885.png)
   
   **Step 7:** 
   
   ![image](https://user-images.githubusercontent.com/46291282/126345513-fac58a79-dbc0-4139-aa51-3584e9c8f053.png)
   
   **Step 8:** 
   
   ![image](https://user-images.githubusercontent.com/46291282/126345737-7a111f3b-729c-4f41-b590-3c12f26d22b8.png)

   
   


   
   


   
   
   

   
   

   
   



   
   
    
    


   
   
   
   

   
   

   
   



   


  
  

  
  

  
  

 
 





   
   
   
   


   
   
   
   

   
   




