  DEPLOYING  STATIC  WEBSITE   USING ACI(DOCKER)  BY CLI AND POWRSHELL
 
Project Overview 
 
Deploy a static website is a userfriendly for create a bar and restaurant. It will also include an "About Us" page, contact information, The primary goal of the Sri Elite Bar and Restaurant project is to establish a premier dining and entertainment destination in rajanna sricilla  The goal is to effectively represent the, provide essential information, and improve customer experience. 
 
Problem Statement 
 
•  Establish a Strong Brand Identity: Develop a strong brand identity that resonates with the target market and positions Sri Elite as a leading lifestyle destination. 
•  Deliver Exceptional Culinary Experiences: Curate a diverse menu featuring innovative dishes and classic favorites, prepared with the finest ingredients and presented with culinary artistry. 
•  Provide Unparalleled Service: Train and empower our staff to deliver exceptional service that exceeds guest expectations. 
•  Create a Vibrant Atmosphere: Design a stylish and inviting ambiance that fosters social interaction and memorable experiences. 
•  Optimize Financial Performance: Achieve sustainable profitability through effective cost management, revenue generation, and strategic marketing initiatives.
 
Project Goals 
 
•	Deploy the BAR AND RESTAURANT website on Azure using CLI &POWERSHELL. 
•	Set up a VIRTUAL MACHINE with Azure Container Registry & Azure Container Instance
•	Use a  image to push the container by using docker file
•	Host the static website on these VMs and make it accessible via azure container instance sever name. 
 
Technologies and Azure Services Used 
 
1.	Azure CLI: Used to create the resource group and Virtual machine. . 
2.	Azure Virtual Machines (VMs): Hosted the Bar and Restaurant. 
3.	Nginx: Used as a web server on both VMs to serve the static content. 
4.	Git: Cloned the website from GitHub onto the VMs using a custom script. 
5.	Custom Script Extension: Used to automatically configure the VMs upon deployment. 
 
 
 
 
Project Steps 
 
1.	Website Development 
 
•	Bar and Resaturant: A static website enabling customers to explore the order , tasty and food essential drinking
 
2.	Deploying the Website on GitHub 
 
•	The bar and restaurant was uploaded to a public GitHub repository 
 
3.	Azure Deployment Using CLI & POWERSHELL
 
•	Resource Group: Created using Azure CLI to hold all the resources. 
•	Virtual machine: Created using Azure CLI to hold the virtual machine
•	Azure Container Registry
•	Azure Container Instance
   
4.	Virtual Machines Setup 
 
•	VM 1: Created in Availability Zone 1 using Azure Portal. Configured with: 

                      Custom Script Extension to clone the website from GitHub. 
                       Azure Container Registry and Azure Container Instance 
 
5.	Load Balancer Configuration 
 
•	Load Balancer: Configured to distribute a push the images into azure container registry by use the VM and ACI 
•	 Defined to  HTTP traffic (port 80) across the VMs. 
In ACR enable the respository to connect the ACI for sever name to deploy the website 
 
6.	Testing and Accessing the Website 
 
•	After push the image to the ACI  it will show the website became accessible via the github to  Customers can access the website on the server 
 






How to Use Bar and Restaurant Website: 
 
1.	Explore our website. 
2.	Select the food item  or drinking items which you want from the website. 
3.	Confirm your order to book a table. 
4.	If you are satisfied with our service can follow us. 
 
Azure Services and Tools Used: 
 
•	Azure CLI: Resource group creation and managemen. 
•	Azure Virtual Machines: Hosting the website on multiple VMs. 
•	Azure Container Registry
•	Azure Container Instance 
•	Nginx: Web server for hosting static content. 
•	Git: Version control and cloning the website onto VMs. 
•	Custom Script Extension: Automated configuration of VMs. 
 
Live Website and Resources 
 
•	Website Link: bar and restaturant
 
•	Project Video Link: Project video 
 
Screenshots: 


        Created Resource Group Screenshot
            

Resource group in portal
 
 
       
   Create the Virtual Machine
  
 
         
         Created Virtual Machine in portal
 
   
       
        Created The Azure Container Registry


 


 


 Created the azure container registry in portal

 
























 Website Home Page Screenshot 
   
  
  


 Food page after deployment
    
 
  Beer page after depolyment
  
 
         


  Reservation page after depolyment
 
  
       

Contact page after depolyment
 
  
 
 
 
 
 
Conclusion 
 
This sample business plan provides a comprehensive roadmap for launching and operating a successful Bar and Restaurant . By following the outlined steps and utilizing the provided resources, entrepreneurs can create a strong foundation for their business and achieve long-term success. 
 
 
 
