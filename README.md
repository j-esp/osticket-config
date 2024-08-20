![image](https://github.com/user-attachments/assets/447ab34c-5488-482d-9ec6-44261a54a2ab)

<h1>osTicket - Configurations</h1>
This lab demonstrates the necessary steps to configure osTicket for effective use as a ticketing system.

<h2>Technologies and Platforms</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- osTicket 

<h2>Operating Systems </h2>

- Windows 10 Pro (22H2)


<h2>Configuration</h2>

![image](https://github.com/user-attachments/assets/cb9458f1-b354-40ef-8f4f-bc188958650b)
![image](https://github.com/user-attachments/assets/cbbb7bd0-6a8f-4532-b40d-9971df23f94b)
![image](https://github.com/user-attachments/assets/bbbc34f2-4f78-4712-9644-c5d48bd7c0cb)
![image](https://github.com/user-attachments/assets/de768b50-fcb1-4bc9-97c7-c6abf2343d89)

<p>
After installing osTicket, I will configure it as a functional ticketing system. This involves switching between the Admin and Agent panels, as they have distinct settings. Initially, I created a new "Supreme Admin" role with full permissions.
</p>

![image](https://github.com/user-attachments/assets/ee4af695-648a-45f9-923b-828c7b12b44f)

<p>
Next, I will create a new department for System Administrators. In the Admin panel, go to the Agents menu, select Departments, and then create the new department. 
</p>

![image](https://github.com/user-attachments/assets/79683f6e-1134-4750-be58-9519bb02ce27)

<p>
Next, create a Level II Support team to complement the existing Level I Support team in osTicket. This is done in the Admin panel by navigating to the Agents menu and selecting Teams. 
</p>

![image](https://github.com/user-attachments/assets/ab66a4bc-1083-48d3-962b-36aa8226a326)
![image](https://github.com/user-attachments/assets/33b82ab8-64bf-4c2c-ba3f-2bb8e097ba8d)

<p>
To resolve incoming tickets, new agents must be added in the Admin panel. Navigate to the Agents menu, select "Add New Agent," and create account credentials for the new agents—Jane and John Doe, in this case. 
</p>

![image](https://github.com/user-attachments/assets/ce947dc5-5dad-4c08-9e07-df1310ae309e)
![image](https://github.com/user-attachments/assets/414898b0-0a06-4aa0-82ab-e0e9972f1bb7)

<p>
Conversely, new users must be created for ticket submission to enable agents to handle them. In the Admin panel, select "Add User" and create account credentials for the new users—Karen and Kan, in this case.
</p>

![image](https://github.com/user-attachments/assets/1ec76726-b7d8-4e02-821c-142b683b6f2a)

<p>
Service Level Agreements (SLAs) will be established to categorize tickets relative to their level of impact. This is done in the Admin panel under the "Manage" menu. Click on "SLA" to create the required SLAs—SEV-A, SEV-B, and SEV-C. Each SLA has a different resolution timeframe: 1, 4, and 8 hours, respectively. 
</p>

![image](https://github.com/user-attachments/assets/87034498-1966-47b5-80c3-7afaebb5262d)

<p>
Finally, Help Topics are created to help users categorize their issues, providing Agents with a clearer understanding of the ticket's content. To add Help Topics, go to the "Manage" menu in the Admin Panel, select "Add New Help Topic," and enter the relevant categories. In this activity, I created the following Help Topics: Business Critical Outage, Personal Computer Issues, Equipment Reset, and Password Request. 
</p>

<h2>osTicket Configurated</h2>
With osTicket configured, it is now fully operational as a ticketing system, capable of creating and resolving tickets as it would in a real-world environment. 
