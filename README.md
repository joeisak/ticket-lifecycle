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

<p>
<img src="https://i.imgur.com/IhP25ti.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, I opened the browser up and went to localhost/osticket. From there, there's an option on the right side of the page to "open a new ticket". Once the user clicks that, they are prompted to enter their information as a registered user. In the previous project https://github.com/joeisak/post-install-config I created two users that can submit tickets, "Ken Ken" and "Karen Karen". After placing the user's information, the user can select a help center topic (three of which were made in the previous project) if applicable, along with a summary of the issue. In this example, a "Business Critical Outage" was selected and a brief description of the issue was given.
</p>
<br />

<p>
<img src="https://i.imgur.com/IUK1zo5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I'm going to log into the account of a help desk user "Jane Doe" that I created to take care of the new ticket. When I login, I'm immediately able to see the new open ticket.
</p>
<br />

<p>
<img src="https://i.imgur.com/ObzBw7z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I updated the priority to "Emergency" and the SLA Plan to "Sev-A". Then, I assigned the ticket to System Administrators. Help desk users are able to update these by clicking on the blue text next to each of the categories. 
</p>
<br />

<p>
<img src="https://i.imgur.com/YeSXdP1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I replied to the ticket by stating that system administrators will be the one's currently handling the ticket.
</p>
<br />

<p>
<img src="https://i.imgur.com/CWWtHFV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After having "Jerry from System Engineering" resolve the issue, I posted the update to the ticket and at the bottom of the page there is an option to close the ticket. I selected that option and now the open ticket should now be closed.
</p>
<br />
