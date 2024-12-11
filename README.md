<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
In this home lab, I will demonstrate the Ticket and Ticket Life Cycle in osTicket by simulating a series of made-up scenarios as both an end-user and a help desk agent, working through tickets from intake to resolution.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

Admin/Analyst Login Page:  
[http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)

End Users osTicket URL:  
[http://localhost/osTicket](http://localhost/osTicket)

### 1. Creating and Managing Tickets

In this lab, we will create tickets as end users, observe their properties, and respond as help desk agents.

#### Task 1: Change Department Settings
- Change the SysAdmins Department to a Top Level Department.
- DELETE the Maintenance Department (not archive).

#### Task 2: End-User Ticket Creation
As an end-user, create the following ticket:
- **Issue**: Entire mobile/online banking system is down  
![r1](https://github.com/user-attachments/assets/f566609f-7fbd-473d-95dd-0e94f9142df4)

#### Task 3: Help Desk Agent View
As a Help Desk Agent (John), observe the ticket’s properties:
- Priority
- Department
- SLA
- Assigned To  
![r2](https://github.com/user-attachments/assets/7fde7ea4-0b60-43cc-8e9f-f523c8d8e9b2)

#### Task 4: Set Ticket Properties
- Set the ticket properties:
  - **Priority**: Sev-A (1 hour, 24/7)
  - **Department**: Online Banking  
![r3](https://github.com/user-attachments/assets/7cae305c-5449-4cbc-b5e0-c9c7c071a111)

#### Task 5: Ticket Observations
Attempt to observe the ticket again as "John". Can you view or change the ticket?

#### Task 6: Work the Ticket
Work the ticket to completion as Jane:  
![r4](https://github.com/user-attachments/assets/2cdd58f4-99ff-4452-b9d2-50e0b6f3d740)

---

### 2. Creating and Managing Additional Tickets

#### Task 1: End-User Ticket Creation
As an end-user, create the following ticket:
- **Issue**: Accounting department needs Adobe upgrade, broken

#### Task 2: Help Desk Agent View
As a Help Desk Agent (John), observe the ticket’s properties:
- Priority
- Department
- SLA
- Assigned To

#### Task 3: Set Ticket Properties
- Set the ticket properties:
  - **Priority**: Sev-B (4 hours, 24/7)
  - **Department**: Support  
![r5](https://github.com/user-attachments/assets/ab21351f-d4b7-4298-b89a-dd0423faa834)

#### Task 4: Work the Ticket
Work the ticket to completion as John:  
![r6](https://github.com/user-attachments/assets/d89b0d76-7da6-4f06-9683-ad95fd06c3f9)

---

### 3. Additional Ticket Management

#### Task 1: End-User Ticket Creation
As an end-user, create the following ticket:
- **Issue**: CFO’s laptop will no longer turn on

#### Task 2: Help Desk Agent View
As a Help Desk Agent (John), observe the ticket’s properties:
- Priority
- Department
- SLA
- Assigned To

#### Task 3: Set Ticket Properties
- Set the ticket properties:
  - **Priority**: Sev-B (4 hours, 24/7)
  - **Department**: Support

#### Task 4: Work the Ticket
Work the ticket to completion as John:  
![r7](https://github.com/user-attachments/assets/eb7d543f-12e8-47f3-9dcf-02be72284a6c)

---

<h2>Takeaways and Key Skills Developed</h2>

In this project, I demonstrated the ticket lifecycle in osTicket by creating and resolving tickets as both an end-user and a help desk agent. I configured ticket properties such as priority, department, and SLA and worked through each stage of the lifecycle: intake, assignment, communication, and resolution. This hands-on experience helped me understand the full process of ticket management, including configuring workflows and roles, as well as observing how tickets are managed and resolved from start to finish within a ticketing system.
