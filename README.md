<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
Configuring Roles

![image](https://github.com/user-attachments/assets/f20aeafe-1162-4284-9122-5bc5e5603ab5) ![image](https://github.com/user-attachments/assets/343774b9-417e-400a-af9f-9f5146c64fc7) ![image](https://github.com/user-attachments/assets/c13cf4a6-6771-449e-a9c7-2c6eb4ef4807) ![image](https://github.com/user-attachments/assets/4fa75f10-7ab2-4204-9cf8-f69590304d61) ![image](https://github.com/user-attachments/assets/7a42f68a-2d65-4e17-aa2a-d52e2bf285ec) ![image](https://github.com/user-attachments/assets/128c9c2e-cc54-4d15-a1ce-659729c25289) ![image](https://github.com/user-attachments/assets/5cd2dee6-455b-4c79-a09b-94058f8dbe3b) ![image](https://github.com/user-attachments/assets/1a545317-b562-45e1-8429-f0f9c551ea87)

 








</p>
<p>
In the configuring roles section, I'm just grouping permissions together, and giving permissions to certain groups of people. Such as the Agents. The above pictures shows the steps taken to configure these roles. I created a new role..."Supreme Admin" and essentially configured permissions to give them access to every permission that was available. The last picture shows that the Supreme Admin position has been successfully added.
</p>
<br />
Configuring Departments
<p>

![image](https://github.com/user-attachments/assets/1c3d2d26-be7a-44db-96ef-2b3eaa2360dd) ![image](https://github.com/user-attachments/assets/dbbf94b6-62b2-4e20-8d3f-7845d408d0cc) ![image](https://github.com/user-attachments/assets/114ae767-f631-4fd5-a1de-ef51b9710cfc) ![image](https://github.com/user-attachments/assets/6f91f765-0fd1-401c-8fe4-1d4d50a25360) ![image](https://github.com/user-attachments/assets/2e46e71a-cc65-4e95-b494-c960e6386ae1) ![image](https://github.com/user-attachments/assets/88fbfe2d-b10d-4070-af3e-efe80bb5a413)






</p>
<p>
The above photos just shows me successfully creating a Systems Administration department.
</p>
<br />
Configuring Teams
<p>

![image](https://github.com/user-attachments/assets/dadb8c15-9c65-46e3-ad9a-50cadfebaf39) ![image](https://github.com/user-attachments/assets/1cfef475-78dd-4b90-affe-796b7e75f46e)


</p>
<p>
This section is very easy and simple. I created a few teams just for the purpose of having different people working different departments to handle various needs. The above is an example of an "Online Banking" team created to handle online banking issues. From the Admin panel, I went to "Agents" and then "Teams". Clicked "Add New Team", and followed the appropriate steps to create the online banking team.
</p>
<br />
Configure Agents
<p>

![image](https://github.com/user-attachments/assets/b12510d4-7c31-454e-9ff7-488af3e6ec50) ![image](https://github.com/user-attachments/assets/5fb9c827-b7a2-44c6-9c42-9c022646c818) ![image](https://github.com/user-attachments/assets/6a3112f7-cb70-463f-af9b-d308062a4b75) 
![image](https://github.com/user-attachments/assets/910b445d-ffcb-4548-a780-ce48d3556b62) ![image](https://github.com/user-attachments/assets/fef272c3-7e2d-4d07-ac0d-13b6beaadff6)


In this section, I am simply creating new agents, assigning them to appropriate departments, and giving permissions to navigate throughout osTicket for certain tasks.

  
</p>












# post-install-config
