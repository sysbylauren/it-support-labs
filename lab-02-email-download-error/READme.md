# Lab 02: Email Attachment Download Issue

## 📌 Scenario Overview
* **Ticket ID:** INC579697
* **User:** Andrew Kim (`akim@servicedesk-simulator.com`)
* **Department:** Sales (Remote)
* **Impact:** High — User is unable to open or download sales contracts sent by clients, blocking work.
* **Issue Description:** User receives emails normally, but clicking attachments produces an error or no response.

---

## 🛠️ Step-by-Step Troubleshooting & Resolution

### Step 1: Initial Ticket Assessment & Verification
* Reviewed ticket details to identify the affected user and business impact.
* Confirmed the issue is isolated to downloading/opening attachments rather than general email flow.

<img width="580" height="328" alt="Screenshot 2026-07-23 at 14 51 45" src="https://github.com/user-attachments/assets/64f66a5b-c881-413f-9415-ca43a8add874" />


### Step 2: Diagnostic & Environment Check
* Connected to the user's remote machine.
* Went to the mail client and proceeded to repair.

<img width="613" height="832" alt="Screenshot 2026-07-23 at 14 53 57" src="https://github.com/user-attachments/assets/2283b471-a83d-4b2f-8eb6-cd5fc9b0fd0b" />


### Step 3: Resolution & Verification
* Verified with the user that contracts can now be downloaded successfully.

<img width="613" height="30" alt="Screenshot 2026-07-23 at 14 54 13" src="https://github.com/user-attachments/assets/6f5adf0e-16c2-47f0-9527-3d4d97d07575" />


## 🎯 Final Outcome
* **Status:** Resolved
* **Root Cause:** *Mail client needed to be repaired/reset*
* **Action Taken:** Reconfigured attachment handling and verified file access.


## 💡 Key Takeaways
* **Prioritize Business Impact:** Issues blocking revenue-generating work (like contract processing) require immediate triage and clear communication.
* **Verify Local vs. Server:** Distinguishing between email reception issues and local application/file-handling errors saves time during diagnostics.
