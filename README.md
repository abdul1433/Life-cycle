<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />




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

<h2>Lifecycle Stages</h2>



First we will create tickets as an end user (customer) and then resolve it as an agent
<br />


Before we create tickets as an end user we will need to give access to the users so that they can create their tickets


Login as an agent 

Go to "http://localhost/osTicket/scp/login.php"


<p>
<img src="https://i.imgur.com/nOcQLH9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />


Go to user directory 

Agent Panel >Users >User Directory

<p>
<img src="https://i.imgur.com/kWhu3ce.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

In order to give access to the users to create tickets we will have to register them 

Select the users and go to more >register


<p>
<img src="https://i.imgur.com/eAyUvyj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>




Once the users are registered you will need to activate them to login as a user and create tickets


<p>
<img src="https://i.imgur.com/Ffr79zO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 
 Go to user's main page >More >Manage Account Access
 
 Set up the credintials and Save Changes
 
 
 
 <p>
<img src="https://i.imgur.com/Xi9f0hC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


 
 <p>
<img src="https://i.imgur.com/puYX13b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Repeat the same process for another User


Once you are done with regitration part open a new tab on the browser and go to "http://localhost/osTicket/open.php"

Go to "Open a New Ticket" and login as Ken (Enter the credentials you created while giving access to the user)



 <p>
<img src="https://i.imgur.com/tPeXGiO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


Once you are logged in select the Help Topic from the drop down menu and select "Personal Computer Issues"

Name the Issue Summary as "Entire Account Dept Adobe Reader not working"

Descibe the issue in details and create the ticket


<p>
<img src="https://i.imgur.com/8c8X0zj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


Next Sign out as ken and sign in as karen pretending to be the another user

Select the help topic from the drop down menu and select "Business Critical Outage"

Name the issue summary and describe the issue in details and create the ticket 


<p>
<img src="https://i.imgur.com/D4RXo2u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>




<h3>Assignment and Communication</h3>

Log in to osTicket portal as admin

Once logged in, you will see the view of tickets in a que

Assign the tickets to a particular agent and update priority levels on the ticket

In the body of the ticket, type in the details to update the status of the issue


<p>
<img src="https://i.imgur.com/Es8qrmI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


<p>
<img src="https://i.imgur.com/38KLYHp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


<p>
<img src="https://i.imgur.com/sVtEkCB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


<h3>Working the Issue</h3>


Log in to osTicket portal as Jane Doe (Agent)

Open the ticket you have to work on

Go to Post Reply Section and then click on Post Internal Note tab

Enter a summary of the note and describe the details in the body of the ticket

Click on Post Note


<p>
<img src="https://i.imgur.com/OFdz7lI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


<p>
<img src="https://i.imgur.com/qXkvQBM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>































