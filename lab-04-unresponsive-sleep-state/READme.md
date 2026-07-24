# Lab 04: Unresponsive Sleep State & User Guidance

## 📌 Scenario Overview
* **Category:** Hardware & OS Support / End-User Communication
* **Objective:** Guide a user through recovering a system stuck in an unresponsive sleep state via step-by-step chat support.
* **Impact:** Critical — System non-responsiveness prevents user access, requiring immediate step-by-step recovery guidance.

---

## 🛠️ Step-by-Step Troubleshooting & Resolution

### Step 1: Ticket Triage & User Contact
* Opened the support ticket, assigned it to myself, and initiated direct chat support with the user.
* Informed the user that I was assisting with their unresponsive machine and verified their current status.
<img width="577" height="356" alt="Screenshot 2026-07-23 at 14 45 04" src="https://github.com/user-attachments/assets/11270c1c-0d34-4b5d-a371-f4be3f0993de" />



### Step 2: Diagnostic & Troubleshooting via Chat
* Identified that the endpoint was hung in a deep sleep state and not responding to standard mouse or keyboard inputs.
* Provided clear, broken-down instructions in the chat guiding the user through performing a manual hard reboot:
  1. Press and hold the physical power button on the computer for 10–15 seconds until the power light turns off completely.
  2. Wait 10 seconds to allow internal power to clear.
  3. Press the power button once normally to power the system back on.



### Step 3: Verification & Power Settings Adjustment
* Verified with the user via chat that the system booted back up successfully into Windows without error.
* Checked power management settings (Power Options / Fast Startup) to ensure display and sleep timers were optimized to prevent future lockups.
* Logged the communication and resolution steps in the ticket work notes.
* Confirmed the user was fully operational and closed the ticket.
<img width="263" height="614" alt="Screenshot 2026-07-23 at 14 50 14" src="https://github.com/user-attachments/assets/a10aa7b8-69dd-4462-bd11-3b1c7c7ee2f5" />


## 🎯 Final Outcome & Resolution
* **Status:** Resolved
* **Root Cause:** System entered a deep sleep/power state lockup that prevented hardware interrupts from registering through standard peripherals.
* **Resolution Action:** Guided the user through disconnecting peripheral hardware and performing a 30-second power-button hard reset to drain residual power and reboot the system into normal operation.


## 💡 Key Takeaways
* **Clear User Communication:** Breaking down multi-step physical troubleshooting actions (like hard reboots) into simple, numbered steps in chat helps standard users perform recovery safely.
* **Triage & Escalation:** Distinguishing between system power hangs vs. actual hardware failure ensures quick resolution times without unnecessary hardware dispatches.

