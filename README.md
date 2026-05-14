# aws-iam-user-permissions-project
Created an IAM user, IAM group, and applied least‑privilege permissions. Tested allowed vs denied actions and enabled MFA for secure access.

# AWS IAM User & Permissions Project

This project demonstrates how to create and manage IAM users, groups, and permissions in AWS using the principle of least privilege. The goal was to understand how access control works by creating a restricted user and testing what actions they can and cannot perform.

---

## 🚀 What I Built

### ✔ Created an IAM User
- Created a new IAM user with console access
- Required the user to reset their password at first login

### ✔ Created an IAM Group
- Created a group named **ReadOnlyGroup**
- Attached the AWS-managed **ReadOnlyAccess** policy

### ✔ Assigned the User to the Group
- Added the new user to the ReadOnlyGroup
- Ensured the user only had read-only permissions across AWS services

### ✔ Logged In as the IAM User
- Used the IAM console login link
- Reset the password as required
- Verified the user could sign in successfully

### ✔ Tested Permissions
**Allowed actions:**
- View S3 buckets (if any exist)
- View EC2 instances
- View AWS resources across services

**Denied actions (expected):**
- Creating S3 buckets
- Launching EC2 instances
- Deleting or modifying resources

These “Access Denied” messages confirmed that the ReadOnlyAccess policy was working correctly.

### ✔ Enabled MFA (Security Best Practice)
- Assigned an MFA device to the IAM user
- Scanned QR code using an authenticator app
- Verified MFA codes to complete setup

---

## 🎯 What I Learned
- How IAM users and groups work
- How AWS-managed policies control access
- How to apply least privilege
- How to test permissions by logging in as the restricted user
- How MFA improves account security

---

## 🧩 Skills Used
- IAM Users & Groups  
- AWS Managed Policies  
- ReadOnlyAccess Permissions  
- MFA Configuration  
- Security Best Practices  

---

## 📌 Summary
This project shows how to properly set up secure IAM access in AWS. By creating a read-only user and testing their permissions, I gained hands-on experience with AWS identity management and security controls.
