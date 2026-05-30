# Active Directory Basics

## What Is Active Directory?

Active Directory is Microsoft's directory service used to centrally manage users, computers, groups, permissions, and authentication within an organisation.

It allows IT teams to control who can access company systems and resources.

## Common 1st Line Support Tasks

### Password Reset

Used when a user has forgotten their password or cannot log in.

Steps:

1. Verify the user's identity according to company procedure.
2. Locate the user account in Active Directory.
3. Reset the password.
4. Set "user must change password at next login" if required.
5. Ask the user to test login.
6. Document the action in the ticket.

### Account Unlock

Used when an account has been locked after repeated failed login attempts.

Steps:

1. Verify the user's identity.
2. Locate the account in Active Directory.
3. Confirm the account is locked.
4. Unlock the account.
5. Ask the user to attempt login again.
6. Check whether the lockout repeats.

Common causes of repeated lockouts:

- Old password saved on a mobile device
- Outlook using cached credentials
- VPN client using old credentials
- Mapped drive using old credentials
- Repeated incorrect password attempts

### Group Membership

Groups are used to manage access for multiple users at once.

Example:

A user needs access to the Finance shared drive. Instead of giving direct access to the individual user, IT may add them to the correct Finance security group.

Steps:

1. Confirm the access request is approved.
2. Identify the correct group.
3. Add the user to the group.
4. Ask the user to sign out and back in if needed.
5. Confirm access works.
6. Document the change.

## Authentication vs Authorisation

### Authentication

Authentication proves who the user is.

Examples:

- Password
- MFA prompt
- Authenticator app
- Fingerprint
- Facial recognition

### Authorisation

Authorisation determines what the user is allowed to access after they have authenticated.

Example:

A user can log in successfully but cannot access the Finance shared drive. This is likely an authorisation or permissions issue rather than an authentication issue.

## Common Scenario

### User Can Log In But Cannot Access A Shared Drive

First checks:

1. Is the issue affecting one user or multiple users?
2. What error message is the user seeing?
3. Could the user access it previously?
4. Does the user have the correct permissions or group membership?
5. Are other users able to access the same resource?

## Escalation Criteria

Escalate if:

- Multiple users cannot authenticate
- Active Directory services appear unavailable
- Permissions are unclear or not approved
- Repeated lockouts continue after basic checks
- Security concerns are identified

## Interview Questions

### What is Active Directory?

> Active Directory is Microsoft's directory service used to centrally manage users, computers, permissions and authentication within an organisation.

### What are some common 1st line Active Directory tasks?

> Common tasks include password resets, account unlocks, checking group membership, creating user accounts and helping users regain access to systems.

### Why are groups used in Active Directory?

> Groups allow permissions to be assigned to multiple users at once rather than managing each user individually.

### What causes account lockouts?

> Account lockouts are often caused by repeated incorrect password attempts or old credentials stored in applications, mobile devices or VPN clients.

### What is the difference between authentication and authorisation?

> Authentication verifies a user's identity, while authorisation determines what resources and systems they can access once authenticated.

### A user can log into Windows but cannot access a shared drive. What would you check?

> I'd determine whether the issue affects one user or multiple users, check group membership and permissions, review any error messages and confirm whether the user previously had access.

### What would you do if a user could not log in?

> I'd gather information about the error, verify the user's identity, determine whether the issue is related to passwords, account lockouts, MFA or connectivity, and then troubleshoot or escalate as appropriate.


## Interview Summary

A strong 1st line explanation:

> Active Directory is used to centrally manage users, computers, permissions, and authentication. At 1st line level, common tasks include password resets, account unlocks, checking group membership, and helping users regain access to the systems and resources they are authorised to use.
