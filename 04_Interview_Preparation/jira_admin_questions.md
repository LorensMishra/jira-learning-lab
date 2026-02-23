# Jira Admin Questions

## 🔹 1. What are Jira Schemes?

Schemes control how Jira behaves inside a project.

### Types:

| Scheme | Purpose |
|--------|---------|
| Workflow Scheme | Controls issue flow |
| Permission Scheme | Controls access |
| Notification Scheme | Controls alerts |
| Screen Scheme | Controls visible fields |

### Flow:

Project  
⬇  
Linked to  
⬇  
Scheme  

📝 Note:
Admin uses schemes to manage system structure.

---

## 🔹 2. Permission Scheme

Defines who can do what.

### Example:

| Action | Role |
|--------|------|
| Create Issue | Developer |
| Edit Issue | Team Lead |
| Delete Issue | Admin |

📝 Note:
Ensures security & control.

---

## 🔹 3. Role vs Group

| Role | Group |
|------|-------|
| Project-level | Global-level |

Example:

Role → Developer  
Group → Company Employees  

---

## 🔹 4. Screens

Control fields shown during actions.

### Types:

Create Screen → While creating issue  
Edit Screen → While editing issue  
View Screen → While viewing issue  

### Flow:

Create Issue  
⬇  
Screen Appears  
⬇  
User Enters Data  

---

## 🔹 5. Field Configuration

Controls:

✔ Required Fields  
✔ Hidden Fields  

Example:

Make "Priority" mandatory.

---

## 🔹 6. Automation

Used to reduce manual work.

### Example Rule:

Issue Created  
⬇  
Auto Assign to Manager  

### Steps:

Project Settings  
➡ Automation  
➡ Create Rule  

---

## 🔹 7. Workflow Transition

Movement between statuses.

### Flow:

To Do  
⬇ Start  
In Progress  
⬇ Test  
Testing  
⬇ Approve  
Done  

📝 Note:
Each arrow = Transition

---

## 🔹 8. Custom Fields

User-created fields.

Example:

Client Name  
Project Type  

---

## 🔹 Interview Tip

✔ Admin = Control + Structure  
✔ Explain using flow  
✔ Mention automation knowledge  