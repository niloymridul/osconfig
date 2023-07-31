<p align="center">
<img src="https://github.com/niloymridul/osprereqs/assets/139414980/14148678-3d21-4da3-acb6-9cfb9ddf9903" height="40%" width="40%" alt="Kali Linux logo"/>
</p>

<h1> osTicket - Set-Up Configuration & Real Life Ticketing Scenarios</h1>
Welcome to the osTicket second tutorial. This part of the tutorial will be detailing the post setup of osTicket and usage of osTicket when used in real-life scenarios.<br />

<h2>Environments & Softwares Used</h2>

- Microsoft Azure
- osTicket
- Virtual Machines
  
<h2>Project Steps</h2>

<p>
Welcome back to the second part of the tutorial. This part of the tutorial is where we will give you an understanding of the osTicket interface, the roles in it, and the ticketing system we use to work it. Before we begin please log in to your account. Hopefully, remember the password and username. Feel free to experiment along the way.

First, we are going to configure roles. We will need to make and address a Supreme Admin as that is the person who has total control over everything. Click Admin Panel -> Agents and then click Roles. Go ahead and give it every permission for tickets, tasks, and knowledgebase. Now the person for this role can do anything and everything.

Second, we need to create a department for System administrators. If you are still on the admin page subpage agents please click Departments. All we need is to create the name nothing more. We only need to create the department so just simply type in the name of the department and then create.

Now I want us to go to teams. Still on the Admin panel and still subpage Agents. I want us to click on Add New Team. We are going to make a second team called Level II Support. While Level I support has already been made, we will make another one that will also be a team that can Level I Support can escalate tickets to which makes sense as per the name. You can also write that they can create tickets in both teams in the notes part of the creation/edit section.

From that point we are going to edit user settings so that no one outside of those who have permissions and or are registered can log in to create tickets. Save changes every time you do so.

Next, we are going to make some agents. The same panel but now we will click agents and then agents. We will be able to configure and even login as them. Now we can put them in teams and give them permissions. Feel free to put them in any department you wish. In this case, I am going to an agent called Jane Doe and she will be given all access and you can create a password as well for the agents. Just be sure to set it and remember the password, username, and email. In fact, you should type/write all this information down. I will also make an Agent called John Smith and give some basic permissions. Again, go ahead and fill in the same fields that were needed for Jane Doe. Now you will be able to log in as them.

Following that, we are going to create customers so that we can create tickets for practice and get an understanding of how they work. So now we have to switch back to the Agent Panel so click it all the way at the top. We will click new users and now create two users called Karen & Ken. You do not need to create passwords for them.

The second to last but important thing we need to talk about is SLA. SLA is a service-level agreement. Go back to Admin Panel -> Manage -> SLA. We will add three of them as most companies will deal with various degrees. SLA plans are categories for placing help desk tickets. Some are very important such as the entire website that store based company has is down which is an issue that needs to be fixed immediately. Some issues are minuscule such as a user needing help resetting their password or their computer won't connect to the internet as it is disconnected. It's still something that needs to be fixed but it's something that can be dealt with later. Each SLA plan will have its urgency and time of importance which is why we give them Severity levels hence SEV A to C.

The last thing is help desk topics. Go to Help Topics in the same panel and subpage. We are going to create a few help topics as these are categories for customers such as Ken and Karen to write to the company about. We are going to write several help topics for the following topics. Business Critical Outage, Personal Computer Issues, Equipment Request & Password Reset. Save it after creating each one. Now we have finished setting up the basics of OsTickets.

Now, let's start trying to make some basic tickets for us to edit. Let's say we make a ticket. First, go to localhost/osTicket. Then we will start writing out some tickets and be sure to use the customer emails we used before using our customer accounts. Type in the email information and write up a ticket. In this first ticket, we will talk about personal computer issues and then we will create it. After creating it, we can go back to our admin panel with our admin account, go to the agent panel and then go to the ticket channel. 

Now we can try and solve it, give it an SLA severity level, and add it to other departments as we are an admin ourselves. I will also assign it to Level II Support. We can also log in as Jane as she is an agent we have created before. I also went ahead and updated her permissions and she is a part of the Level I & II team so she should be able to get the ticket. Go ahead and log into her account. And then go to tickets. We will make reply to this ticket and resolve it. Thus ending it. 

This is how tickets work. Go ahead and switch to the admin account and look at the closed ticket panel. Now we can look at it and see how and why it is closed. Now feel free to experiment between creating tickets and logging in accounts and assigning tickets.
</p>
