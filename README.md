
Since we will be switching from Admin Panel(sets up the ticketing system,defines roles,SLAs etc) to Agent Panel(working ticket and helping users).
First make sure you log into osTicket as Admin Panel using the credentials that you set for the Admin in the previous tutorial.
You can also use the Url: http://localhost/osTicket/scp/login.php  to login.

![image](https://user-images.githubusercontent.com/129979322/235323718-2145b962-6e84-4b25-9f09-f14fe87aad65.png)

Next step is to configure Roles.
Here is the link for more information: https://docs.osticket.com/en/latest/Admin/Agents/Roles.html.

![image](https://user-images.githubusercontent.com/129979322/235324245-50d5d5a0-a13d-4cc5-8702-3d4cafc5fa70.png)

Go to the Admin Panel and that button will switch from "Admin Panel" to "Agent Panel".Then go to Agents>Roles> Add New Role

![image](https://user-images.githubusercontent.com/129979322/235324201-ddb136e8-07a8-40db-a7d5-b56eae99e94a.png)

![image](https://user-images.githubusercontent.com/129979322/235324521-e2b817f3-150b-47df-bfd2-6690b8941566.png)

Now name the new role "Supreme Admin" and select all permissions for Tickets,tasks,and knowldgebase,then click save.

![image](https://user-images.githubusercontent.com/129979322/235325226-38875221-1b8b-45c3-aeb7-7eed68afb4ff.png)
![image](https://user-images.githubusercontent.com/129979322/235325271-a4dc89e5-832b-481d-b5fa-f9032cc2bee9.png)

Then go to departments panel and add a new department.
Here is the link for better understanding: https://docs.osticket.com/en/latest/Admin/Agents/Departments.html
Name it "system Admin" and click create with default settings.

![image](https://user-images.githubusercontent.com/129979322/235325887-d203fcc6-f45c-49c2-8f9f-cb67d2f69e60.png)
![image](https://user-images.githubusercontent.com/129979322/235325942-58336e8b-1ef0-4db6-8551-9a647f488c6b.png)
![image](https://user-images.githubusercontent.com/129979322/235325987-a9981948-236c-438c-a43e-e15226bda39a.png)

Now go to the Teams panel and click add new team.https://docs.osticket.com/en/latest/Admin/Agents/Teams.html
next go ahead and name it "level II Support" and create team.

![image](https://user-images.githubusercontent.com/129979322/235326793-cb0ffb8d-51e4-4962-8c86-b70f4402bc61.png)

![image](https://user-images.githubusercontent.com/129979322/235326864-795b0fdb-0e11-4d5f-9eb5-a16cf0eb146c.png)

Next go to settings>users>settings and make sure the registration Required: Require registration and login to create tickets is unchecked.
So that we can be able to create ticket anonymously.

![image](https://user-images.githubusercontent.com/129979322/235327044-c589eed0-950a-4d79-9855-5901009f7224.png)
 
 We are going to create agents : https://docs.osticket.com/en/latest/Admin/Agents/Agents.html
 Just go to Agents> add new agent
 
 ![image](https://user-images.githubusercontent.com/129979322/235328763-0a581876-1105-44c2-b65a-b6918243d96d.png)
 
 ![image](https://user-images.githubusercontent.com/129979322/235328620-22c99aba-0480-43aa-83eb-23be6fdaa7a0.png)
 
 Next go ahead and give the agent access by clicking on "Access" and add the agent for instance to "system Admin" 
 and for role select "supreme Admin" lastly go to team and add the agent to a "level II support".
 Then create Cara's account as shown below:
 
 ![image](https://user-images.githubusercontent.com/129979322/235328908-885583c8-1d07-4134-8957-73233a835161.png)
 
 ![image](https://user-images.githubusercontent.com/129979322/235329120-1abb62fd-a1e9-4a1c-b960-95041807958b.png)

![image](https://user-images.githubusercontent.com/129979322/235329148-5fc37c02-50f9-4fda-86d2-78e0fcd796f7.png)

Next we will be creating users: https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html

Go ahead and switch to the Agent panel> users> Add a new user

![image](https://user-images.githubusercontent.com/129979322/235817402-fefe8251-fed9-4dc3-b6dd-2ce64220acd4.png)

![image](https://user-images.githubusercontent.com/129979322/235737868-5a01c2f6-7fcf-48b2-bab1-cf5f120e4433.png)

![image](https://user-images.githubusercontent.com/129979322/235737974-e5015784-6f67-4503-9d02-d882d598f11f.png)

Next we are going to configure SLA.Here is the link fore better understanding:
https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html


Go to ADMIN Panel > Manage > SLA > add new SLA Plan

![image](https://user-images.githubusercontent.com/129979322/235817821-6fade18c-6900-48fd-8246-7f743682a287.png)


![image](https://user-images.githubusercontent.com/129979322/235818298-2c00d4ee-82cf-407a-84e0-3c61fff4f593.png)


![image](https://user-images.githubusercontent.com/129979322/235330243-dec3bfca-c19d-489f-84ea-7b0f4ea2fc33.png)

![image](https://user-images.githubusercontent.com/129979322/235330291-9e0a9193-6a1a-4e72-8135-7421e360e907.png)

Now go to "help topics" and add the following topics as shown below

![image](https://user-images.githubusercontent.com/129979322/235330556-992137a1-70f3-47a0-8d39-69edbad0eed2.png)

![image](https://user-images.githubusercontent.com/129979322/235330912-36141a45-7a84-49c9-9775-f3c761c34d0c.png)

In the next tutorial we will be exploring tickets and the ticket lifecycle.


