# Active Directory User Management

## Overview
This document outlines standard procedures for managing user accounts in Microsoft Active Directory, including onboarding, offboarding, access control, and password management. These steps are designed for Tier 1–2 IT Support and Help Desk environments supporting both on-site and remote users.

---

## Tools and Environment
- Microsoft Active Directory Domain Services (AD DS)
- Windows Server
- Remote Desktop (RDP)
- Group Policy Management Console (GPMC)

---

## Common Tasks Performed

### 1. User Account Creation (Onboarding)
**Scenario:** New employee requires system access.

**Steps:**
1. Open **Active Directory Users and Computers (ADUC)**.
2. Navigate to the appropriate Organizational Unit (OU).
3. Create a new user account with:
   - Full name
   - Username (following company naming standard)
4. Set initial password and enforce password change at first login.
5. Add user to required security groups based on role.
6. Verify account creation and login capability.

**Result:**  
User successfully onboarded with role-based access.

---

### 2. Password Reset and Account Unlock
**Scenario:** User unable to log in due to forgotten password or locked account.

**Steps:**
1. Locate user account in ADUC.
2. Reset password and unlock account if locked.
3. Apply password complexity requirements.
4. Inform user securely and confirm successful login.

**Result:**  
User access restored with minimal downtime.

---

### 3. Group Membership and Access Control
**Scenario:** User requires access to shared folders, printers, or applications.

**Steps:**
1. Identify required access level.
2. Add user to appropriate security or distribution groups.
3. Apply least-privilege access principles.
4. Verify access to requested resources.

**Result:**  
Controlled and secure access granted based on job role.

---

### 4. User Account Modification
**Scenario:** Employee role change or department transfer.

**Steps:**
1. Update user details (department, title, manager).
2. Modify group memberships to match new role.
3. Remove unnecessary permissions.
4. Validate updated access rights.

**Result:**  
Access aligned with current responsibilities.

---

### 5. User Account Deactivation (Offboarding)
**Scenario:** Employee exit or contract termination.

**Steps:**
1. Disable user account immediately.
2. Remove group memberships.
3. Reset password to prevent access.
4. Move account to a disabled users OU.
5. Document action for audit purposes.

**Result:**  
System access securely revoked.

---

## Security Best Practices Applied
- Role-based access control (RBAC)
- Least privilege enforcement
- Timely account deactivation
- Password policy compliance
- Audit-friendly documentation

---

## Common Issues and Troubleshooting

| Issue | Resolution |
|-----|-----------|
| User cannot log in | Reset password, unlock account |
| Access denied | Verify group membership |
| Changes not applied | Check replication or group policy refresh |
| Locked account | Investigate failed login attempts |

---

## Outcome and Impact
- Improved identity and access management
- Reduced unauthorized access risks
- Faster user onboarding and issue resolution
- Enhanced support efficiency for remote and on-site users

---

## Role Alignment
This workflow aligns with:
- Remote IT Support Specialist
- Help Desk Technician (Tier 1–2)
- Junior System Administrator
- Network Support Engineer
