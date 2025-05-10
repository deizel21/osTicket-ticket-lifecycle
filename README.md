<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2

<p>
Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php 

End Users osTicket URL: http://localhost/osTicket 

• In this lab, we will be creating tickets as end users
Observing all the ticket properties and responding to them as help desk professionals


•	Change the SysAdmins Department to a Top Level Department
•	DELETE the Maintenance Department (not archive) = creates unnecessary loop of tickets we wont use

________________________________________

• As an end-user, create the following ticket
  Put in Karen’s information including email, phone number, Summary stating entire mobile/online banking system is down and a description. 

•As a Help Desk Agent (john), observe the ticket’s properties
	Priority (Observe the ticket summary to see priority level)
	Department
	SLA
	Assigned To

•Set Properties to the ticket
 Sev-A (1 hour, 24/7)
 Online Banking Department

•Attempt to observe the ticket again as “john”. Can you view or change?

• Work the ticket to completion as jane
As an end-user, create the following ticket
accounting department needs adobe upgrade, broken

• As a Help Desk Agent (john), observe the ticket’s properties
	Priority
	Department
	SLA
	Assigned To

•Set Properties to the ticket
Sev-B (4 hours, 24/7) > Support

Work the ticket to completion as john

________________________________________

As an end-user, create the following ticket
CFO’s laptop will no longer turn on

As a Help Desk Agent (john), observe the ticket’s properties
	Priority
	Department
	SLA
	Assigned To

Set Properties to the ticket
•	Sev-B (4 hours, 24/7)
•	Support

• Work the ticket to completion as john
 Set Properties to all the tickets; do SEV-A (SysAdmins last), observe ticket becomes inaccessible
  Switch to admin panel and assign yourself View-access to Sys Admins
  Switch to agent panel and observe the escalated ticket
  Observe that you can no longer make changes to it

Solve all of the tickets

![image](https://github.com/user-attachments/assets/4d8090b6-4b79-4b05-a578-23807b811554)
![image](https://github.com/user-attachments/assets/49acad81-f529-4fc2-903b-8d86ed136ed6)
![image](https://github.com/user-attachments/assets/0ba5a92b-9401-4e32-8f8d-5696953e439a)


This is the end of the Lab.

</p>
<br />
                      
