# Lab 03: System Time Zone Configuration Issue

## 📌 Scenario Overview
* **Category:** Operating System & Configuration / System Support
* **Objective:** Resolve user issues regarding incorrect clock/calendar times by configuring local system time zones and sync settings.
* **Impact:** High — Incorrect time settings cause scheduled calendar conflicts, incorrect email timestamps, and authentication failures with domain services.

---

## 🛠️ Step-by-Step Troubleshooting & Resolution

### Step 1: Ticket Triage & Self-Assignment
* Reviewed the incoming queue for unassigned tickets and selected ticket **INC579697**.
* Assigned the ticket to myself and updated the status to **In Progress** to inform the user and team that triage had begun.

<img width="575" height="348" alt="Screenshot 2026-07-23 at 14 21 05" src="https://github.com/user-attachments/assets/a38ae15d-9e09-4c5b-88cb-d3c2192c0ed3" />


### Step 2: Time Zone & Clock Adjustment
* Initiated a **Remote Desktop Connection** to the user's workstation to investigate the environment directly.2. Toggled **Set time zone automatically** or manually selected the correct local time zone from the drop-down menu.
* Navigated to **Settings ➔ Time & Language ➔ Date & Time** (and verified Windows Control Panel settings) to assess local clock accuracy against actual user location.
* Forced a manual time synchronization with the domain/NTP time server (`time.windows.com`) to ensure complete accuracy.

<img width="365" height="587" alt="Screenshot 2026-07-23 at 14 23 22" src="https://github.com/user-attachments/assets/44e76552-cff2-49ab-92a7-e86b6cfc448c" />


### Step 3: Verification & Ticket Closure
* Confirmed system time aligned with local time zone requirements.
* Added resolution documentation to the ticket notes and marked ticket status as **Resolved/Closed**.

<img width="615" height="838" alt="Screenshot 2026-07-23 at 14 24 07" src="https://github.com/user-attachments/assets/7937badb-05cc-42dd-804b-7343b2d1949f" />


## 🎯 Final Outcome
* System time zone updated successfully to reflect the correct local time.
* Verified that system logs, calendar events, and timestamped communications align accurately.


## 💡 Key Takeaways
* **Authentication Impact:** Kerberos and domain authentication protocols strictly rely on synchronized clocks; significant time drift can prevent users from logging into network resources.
* **User Support:** Remote users traveling across regions often require quick adjustments or permissions to modify system time settings without admin rights.


