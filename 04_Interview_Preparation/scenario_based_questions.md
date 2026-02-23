# Scenario Based Questions

## 🔹 Scenario 1: Duplicate Issues Created

### Problem:
Multiple users create the same issue.

### Solution Steps:

1. Add Labels
2. Use Automation Rule
3. Notify creator

### Flow:

Issue Created  
⬇  
Check Summary  
⬇  
If Match Found  
⬇  
Alert User  

📝 Note:
Prevents duplicate tracking.

---

## 🔹 Scenario 2: Issue Stuck in Progress

### Problem:
Task remains in "In Progress" for long time.

### Solution Steps:

1. Add SLA Field
2. Create Reminder Automation

### Flow:

In Progress (3 Days)  
⬇  
Auto Reminder  
⬇  
Manager Notification  

---

## 🔹 Scenario 3: Approval Before Closing

### Requirement:
Task should close only after approval.

### Steps:

1. Add Status → Approval Pending  
2. Add Approver Field  
3. Update Workflow  

### Flow:

Testing  
⬇  
Approval Pending  
⬇  
Done  

---

## 🔹 Scenario 4: Auto Assign Issues

### Steps:

Project Settings  
➡ Automation  
➡ Create Rule  

Rule:

Issue Created  
⬇  
Assign to Team Lead  

---

## 🔹 Scenario 5: Priority Based Work

### Solution:

Use Priority Field

Flow:

High Priority  
⬇  
Work First  

---

## 🔹 Scenario 6: Track Work by Department

### Solution:

Use Components

Example:

Frontend  
Backend  
QA  

📝 Note:
Helps in department-wise tracking.

---

## 🔹 Interview Tip

✔ Focus on real problem solving  
✔ Explain step-by-step  
✔ Mention automation usage  