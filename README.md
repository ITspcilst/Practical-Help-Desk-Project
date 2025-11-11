# 🖥️ Practical Help Desk Project – Add User to Windows VM Client01

---

## 📘 Overview
This project demonstrates a real-world **Help Desk support task** in which I was required to create a **local administrator account** on a Windows VM.  
The help desk ticket requested that I add a user named **“Richard”**, enforce a **password change at first login**, and make the user a **local administrator**.  
This task allowed me to practice essential **Windows system administration** and **technical support** procedures used in professional IT environments.

---

## 🧩 Project Ticket Reference

**Ticket:** #4561292  
**Task:** Add user to Windows computer  
**Assigned:** Admin  
**Created:** 07/08/2024  
**Status:** Open  

**Comment:**  
> Hello admin, could you please add a local user ‘Richard’ to the Windows computer.  
> Please create the account so that the user will have to change their password the first time they log in.  
> In addition, please make the user a local administrator.

---

## ⚙️ Environment Used
- **Operating System:** Windows 10 Pro  
- **Environment:** Local system / Virtual lab  
- **Tools Used:**  
  - Local Users and Groups Manager (`lusrmgr.msc`)  
  - Command Prompt (for verification)  
- **Privileges:** Administrator access  

---

## 🪜 My Process
To complete the request, I used the **Local Users and Groups Manager** instead of the traditional Computer Management tool for faster access.  
I opened the **Run** dialog using **Win + R**, typed **lusrmgr.msc**, and pressed **Enter** to launch the user management console.  

Once inside, I selected **Users** and created a new local account named **“Richard.”**  
While creating the account, I assigned a temporary password and enabled the option for the user to **change their password at the next logon**, ensuring compliance with basic security practices.  

After the account was created, I opened the **Properties** of the “Richard” user and navigated to the **Member Of** tab.  
From there, I added the user to the **Administrators** group, granting local administrative privileges.  

Finally, I verified the configuration by switching to the **Richard** account, confirming the password reset prompt on first login, and checking administrator access through the **Command Prompt** using: net localgroup administrators
This confirmed that the user “Richard” was successfully listed as a member of the Administrators group.

---

## 🧠 What I Learned
- How to **create and configure local user accounts** in Windows using `lusrmgr.msc`.  
- How to apply **password management and security settings** for new users.  
- The correct procedure for **assigning users to administrator groups**.  
- Improved my ability to **interpret help desk tickets accurately** and **document technical tasks clearly**.  
- Gained confidence in **Windows administrative tools** and **basic security compliance** for user management.

---

## ✅ Conclusion
This help desk project provided valuable hands-on experience with **user management in Windows**.  
Completing the ticket strengthened my understanding of **system security**, **account permissions**, and **proper documentation** when responding to IT service requests.  
It also reinforced my ability to follow instructions precisely, maintain accountability, and perform administrative configurations confidently — key skills for any IT support or system administration role.

---

## 📸 Screenshot
Below is the screenshot showing the **Richard** account successfully created and added to the **Administrators** group.

![Screenshot of Richard user account setup](C9E9E6CA-E862-442A-A018-8544EB031E0C.jpeg)

---

## 🎥 Demonstration Video
Click below to watch my short video demonstration of the process:  
[🎬 Watch Demonstration Video](https://youtu.be/your-video-link)

---

## 🏷️ Tags
`#HelpDesk` `#WindowsAdministration` `#UserManagement` `#ITSupport` `#PracticalProject` `#CybersecurityFundamentals`

---
