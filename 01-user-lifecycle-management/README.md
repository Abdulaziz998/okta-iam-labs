# Lab 1 — Okta User Lifecycle & Profile Management

Objective
Create and manage user accounts in Okta to simulate identity lifecycle processes including user creation, password reset, deactivation, and audit logging.

This lab establishes the foundation for Okta IAM and identity management labs.

⸻

What is User Lifecycle Management?
User Lifecycle Management is the process of managing user identities from creation to deactivation. This includes:
	•	User onboarding (account creation)
	•	Credential management (password resets)
	•	User updates and maintenance
	•	User offboarding (account deactivation)
	•	Identity activity monitoring

⸻

Lab Steps

Step 1 — Navigate to Users
Go to:
Directory → People

Screenshot: ![User Listed](screenshots/user-listed.png)

Step 2 — Create New User
Click:
Add Person

Configure:
First Name: Faisal
Last Name: Abdi
Username: faisal.abdi@company.com
Primary Email: faisal.abdi@company.com

Click:
Save

Screenshot: ![User Created](screenshots/user-created.png)

Step 3 — Verify User in Directory
Confirm the user appears in the People dashboard.

Screenshot: ![User Profile](screenshots/Profile.png)

Step 4 — Review User Profile
Open the user profile and verify attributes.

Screenshot: ![User Profile](screenshots/Profile.png)

Step 5 — Reset User Password
Click:
Resend Password Email

Select:
Create a temporary password

Ensure:
Sign out user is checked

Click:
Reset password

Screenshot: ![Password Reset](screenshots/password-reset-action.png)

Step 6 — Temporary Password Generated
Verify temporary password is generated and user must change it at next login.

Screenshot: ![Temporary Password](screenshots/temporary-password.png)

Step 7 — Deactivate User
Click:
More Actions → Deactivate

Confirm deactivation.

Screenshot: ![User Deactivated](screenshots/user-deactivated.png)

Step 8 — Monitor System Logs
Go to:
Reports → System Log

Verify events:
Create user
Password reset
Deactivate user

Screenshot: ![System Logs](screenshots/system-logs.png)

Result
User lifecycle operations completed:
	•	User created
	•	Password reset performed
	•	User deactivated
	•	Events verified in logs

Skills Demonstrated
	•	User lifecycle management
	•	Password reset and credential handling
	•	User deactivation
	•	Identity monitoring (logs)
	•	Okta Admin Console usage


Next Lab
Group-Based Access Control (RBAC) using Okta Groups
