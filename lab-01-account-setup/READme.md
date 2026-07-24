# Lab 01: Active Directory & User Onboarding

## 📌 Scenario Overview
* **User / Ticket:** [Jennifer Torres - New Hire Onboarding]
* **Category:** Identity & Access Management
* **Objective:** Provision a new user account in Active Directory and assigned appropriate security group permissions.

---

## 🛠️ Step-by-Step Walkthrough

### Step 1: Initial Ticket Assessment
* Review details of the request and gather required user information (Full Name, Department, Job Title, etc).

<img width="576" height="367" alt="Screenshot 2026-07-23 at 14 30 29" src="https://github.com/user-attachments/assets/00a77c36-fe06-4c11-86cd-709becc7d112" />


### Step 2: User Account Creation
1. Opened **Active Directory Users and Computers**.
2. Navigated to the designated Organizational Unit (OU) for `Engineering`.
3. Created a new user object using standard naming conventions (`jtorres`).
4. Set a temporary password and enabled **"User must change password at next logon."**

<img width="1190" height="344" alt="Screenshot 2026-07-23 at 14 33 52" src="https://github.com/user-attachments/assets/e3d05cf4-f4e6-4020-8379-1be1dfc886db" />


### Step 3: Group Membership & Permissions
1. Added the user to security groups:
   * `Engineering`
   * `VPN-Users`
   * `CodeRepo-Acess`

<img width="718" height="309" alt="Screenshot 2026-07-23 at 14 34 09" src="https://github.com/user-attachments/assets/01ae206e-df57-4b46-9b5a-6a3c86285ea9" />


## 🎯 Final Outcome & Resolution
* Account successfully created and configured.
* Onboarding email sent with temporary credentials and login instructions.
* Ticket status updated to **Resolved**.

## 💡 Key Takeaways
* Forcing password changes on first login ensures compliance with security best practices.
* New Hires have SLA's, so onboarding needs to be timely.
* Create directory account first, then add group memberships.


