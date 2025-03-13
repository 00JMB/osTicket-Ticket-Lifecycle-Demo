<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>

This tutorial outlines the lifecycle of demo tickets from intake to resolution within the open-source help desk ticketing system, osTicket.

---

## Environments and Technologies Used

- **Microsoft Azure** (Virtual Machines/Compute)
- **Remote Desktop**
- **Internet Information Services (IIS)**

## Operating Systems Used

- **Windows 10 (21H2)**

## Ticket Lifecycle Stages

1. **Creation (Intake)**
2. **Assignment and Communication**
3. **Working to Completion**
4. **Resolution**

---

## Preface

Before we begin, here are the two links we’ll need for this process. Open both links in separate tabs:

- **Admin/Agent Login Page:** [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)
- **End Users osTicket URL:** [http://localhost/osTicket](http://localhost/osTicket)

📌 *Ensure you're using the correct panel for each section.*

### 🛠 Initial Cleanup
- **Admin Panel:** Navigate to `Agents > Departments` and delete the "Maintenance" department.![image](https://github.com/user-attachments/assets/16535eff-87dc-4d06-adcd-c0b1ba5d57fb)

---

# **Demo Ticket ❶: Creation (Intake)**

- **End User Panel:** Click `Open New Ticket` and fill in the contact info.
- **Scenario:** The user reports that the *online banking portal is down*, causing a **critical outage**.
- **Details:**
  - **Help Topic:** `Report a Problem`
  - **Issue Summary:** *Entire online banking system is down.*
  - **Description:** *Users cannot access the online banking portal. Those who can access it are unable to log in.*
- Click `Create Ticket`.![image](https://github.com/user-attachments/assets/e89efeb8-e9e7-43f0-b384-feeb7ce8742f)


---

# **Demo Ticket ❶: Assignment and Communication**

- **Admin/Agent Panel:** Log in as `John Doe`, open the new ticket, and review it.![image](https://github.com/user-attachments/assets/16550e18-5973-43c9-87b5-2a7d0e4b61b2)
  
- **Set Ticket Properties:**
  - **SLA Plan:** `Sev-A` (provide a brief reason why it's a critical issue).![image](https://github.com/user-attachments/assets/8da45c92-2328-4dbb-ac8d-a5bd7c472855)
    
  - **Priority Level:** `Emergency`![image](https://github.com/user-attachments/assets/ed2cae2a-01fd-4d61-b248-7a37ddb8c9fd)
    
  - **Help Topic:** Change to `Report a Problem > Business Critical Outage` (with reasoning).![image](https://github.com/user-attachments/assets/b71588fa-8f63-4447-9879-355ea18fb974)
    
  - Refresh the page to see the updated **Ticket Thread**.![image](https://github.com/user-attachments/assets/44358464-4872-4ad4-9240-c71dd0b7bf10)
    
- **Assigning the Ticket:**
  - **Assign to Team:** `Online Banking`
  - Provide reasoning and click `Assign`.![image](https://github.com/user-attachments/assets/5b519a5f-fc9b-4bc8-98dc-ee6da6734cfe)

---

# **Demo Ticket ❶: Working to Completion**

- **Log in as Jane Doe** and open the ticket.
- **Take Ownership:** Click `Assigned to:` and assign the ticket to yourself.![image](https://github.com/user-attachments/assets/522f2126-eb85-46b0-a006-91381852d00e)

- **Troubleshooting:**
  - Hypothesis: A recent update to the online banking portal could have caused the issue.
  - Add a **comment** to the Ticket Thread documenting your investigation.![image](https://github.com/user-attachments/assets/58978be1-a38e-4535-8b7f-be06944fc74a)
 
    **Some time later...**

  - After **reverting the system update** the team lets you know the Online Banking portal is back up and running!
  - Time to **send an email notifying the vendor**, and update the thread again.![image](https://github.com/user-attachments/assets/7036ce60-cf57-4801-983e-88cb776633f6)

---

# **Demo Ticket ❶: Resolution**

- **Mark the ticket as Resolved:**
  - Set **Status** to `Resolved`.
  - Optionally, provide a brief **summary** of the issue and resolution.
  - Click `Close`.![image](https://github.com/user-attachments/assets/6c599b80-a61b-4eff-b5ab-d51d0c7ef7e9)

✅ **Demo Ticket 1 Completed!**

---

# **Demo Ticket ❷: Creation (Intake)**

- **End User Panel:** Click `Open New Ticket` and fill in the contact info.
- **Scenario:** *Accounting department reports issues with Adobe software.*
- **Details:**
  - **Help Topic:** `Report a Problem / Other`
  - **Issue Summary:** *Accounting department needs Adobe upgrade, broken.*
  - **Description:** *Multiple employees in Accounting cannot use Adobe Reader.*
- Click `Create Ticket`.![image](https://github.com/user-attachments/assets/bad3adae-ea98-45a4-baf8-2114edb1dd7c)

---

# **Demo Ticket ❷: Assignment and Communication**

- **Admin/Agent Panel:** Log in as `John Doe`, open the ticket, and review it.![image](https://github.com/user-attachments/assets/0fd60ec0-c592-4514-8389-3dcdd2f62d93)
  
- **Clarification:**
  - Reach out to James in Accounting for more details.
  - James reports that **2 employees can't run Adobe Reader, it crashes immediately after launching**.
  - You advise **restarting their computers**, and James agrees and says he'll have them give it a try after lunch.
    
- **Set Ticket Properties:**
  - **SLA Plan:** `Sev-C` (with reasoning).![image](https://github.com/user-attachments/assets/22f15d9a-1b0c-4a65-ac14-e80b5384f99b)
    
  - **Priority Level:** Keep as `Normal`.
  - **Assign Ticket:** Assign to yourself.

---

# **Demo Ticket ❷: Working to Completion**

- **Update Ticket Thread:** Document troubleshooting steps.![image](https://github.com/user-attachments/assets/255620f0-88a8-4108-955d-29f8c9ef28cb)
  
- **User Follow-up:**
  - James confirms that **restarting fixed the issue**.
  - Update the ticket thread accordingly.[image](https://github.com/user-attachments/assets/cf6697d9-90c3-4bcf-b280-28fd4f8454f7)

---

# **Demo Ticket ❷: Resolution**

- **Mark the ticket as Resolved:**
  - Set **Status** to `Resolved`.
  - Click `Close`.![image](https://github.com/user-attachments/assets/ddebce56-daca-479b-bb5a-15ebb5960066)

✅ **Demo Ticket 2 Completed!**

---

### 🎉 Congratulations! You have successfully completed the osTicket repository thread!.

Need to revisit? Bookmark this guide for future reference. 🚀

