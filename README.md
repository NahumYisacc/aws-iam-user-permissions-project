# AWS IAM User Permissions Project

This project demonstrates how to create and manage IAM users, groups, and permissions in AWS using the principle of least privilege.

## Project Summary
The goal of this project was to build a secure IAM setup by creating a user, assigning them to a group with restricted permissions, enabling MFA, and testing both allowed and denied actions. This simulates real-world access control where users should only have the permissions required to perform their job.

## What I Built
- Created a new IAM user
- Created an IAM group with least‑privilege permissions
- Attached the AWS managed policy ReadOnlyAccess
- Added the user to the group
- Enabled MFA for the IAM user
- Logged in as the IAM user to test allowed and denied actions
- Verified that permissions worked correctly

## Skills Used
- IAM user and group management
- Applying least‑privilege security principles
- Assigning AWS managed policies
- Enabling and verifying MFA
- Testing access permissions through the AWS console
- Troubleshooting AccessDenied errors
- Understanding how IAM policies affect real user behavior

## What I Learned
- How IAM groups simplify permission management for multiple users
- Why least‑privilege access is critical for security
- How MFA adds an extra layer of protection for IAM users
- How to test and validate permissions by logging in as the user
- How AWS responds when a user attempts an action they are not authorized to perform

## Screenshots

### IAM User Created
![IAM User](screenshots/iamuser.png)

### IAM Group Created
![IAM Group](screenshots/iamgroup.png)

### Policy Attached to Group
![Policy Attached](screenshots/PolicyAttachedtoGroup.png)

### User Added to Group
![User Added to Group](screenshots/UserAddedtoGroup.png)

### MFA Enabled
![MFA Enabled](screenshots/assignmfa.png)

### Access Allowed (ReadOnly)
![Access Allowed](screenshots/readonlyaccess.png)

### Access Denied (No Write Permissions)
![Access Denied](screenshots/notallowed.png)
