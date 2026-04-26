# Lab 2 — Okta Group & Access Management (RBAC)

## Objective
Implement Role-Based Access Control (RBAC) in Okta by organizing users into groups and assigning group-based access to applications.

This lab demonstrates scalable identity and access management using group-based permissions instead of individual user assignments.

---

## What is RBAC?
Role-Based Access Control (RBAC) is a method of managing access by assigning permissions to groups instead of individual users.

This allows:
- Centralized access management
- Scalable user access control
- Reduced administrative overhead
- Consistent security enforcement

---

## Lab Steps

### Step 1 — Create Groups

Go to:
Directory → Groups

Create the following groups:

- IT-Support-Team  
- Sales-Team  

Screenshot:
![Groups Created](screenshots/groups-created.png)

---

### Step 2 — Add Users to Groups

Open group:
IT-Support-Team

Click:
Assign people

Add:
faisal.abdi@company.com

Screenshot:
![User Added to Group](screenshots/user-added-group.png)

---

### Step 3 — Verify Group Membership

Confirm user appears in group membership list.

Screenshot:
![Group Members](screenshots/group-members.png)

---

### Step 4 — Add Application (Box)

Go to:
Applications → Browse App Catalog

Search:
Box

Click:
Add Integration → Save

Screenshot:
![Box App Added](screenshots/app-added.png)

---

### Step 5 — Assign Group to Application

Go to:
Applications → Applications → Box → Assignments

Click:
Assign → Assign to Groups

Select:
IT-Support-Team

Click:
Assign → Done

Screenshot:
![Group App Assignment](screenshots/group-app-assignment.png)

---

## Result

Successfully implemented RBAC in Okta:

- Created user groups
- Assigned users to groups
- Added application (Box)
- Assigned group-based access to application

Users now inherit access through group membership instead of direct assignment.

---

## Skills Demonstrated

- Okta Group Management  
- Role-Based Access Control (RBAC)  
- Application Access Management  
- Identity Access Provisioning  
- IAM Best Practices (Group-based access)

---

## Why This Matters

In enterprise environments, IAM teams use RBAC to:

- Control access to applications at scale  
- Reduce manual user assignments  
- Improve security and compliance  
- Manage access using identity groups  

This lab simulates real-world IAM access control workflows used in organizations.

---

## Next Lab

Implement Multi-Factor Authentication (MFA) and Conditional Access Policies in Okta.
