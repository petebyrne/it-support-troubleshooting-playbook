# Password Reset and Account Lockout

## Symptoms

- User cannot log in
- User reports password is not working
- Account locked message appears
- Multiple failed login attempts recorded
- Access to Microsoft 365, VPN, or workstation unavailable

## Troubleshooting Steps

### 1. Confirm User Identity

Before making any account changes:

- Verify the user's identity according to company procedures
- Confirm username and affected systems

### 2. Determine the Issue

Identify whether:

- Password has been forgotten
- Password has expired
- Account is locked
- Multi-factor authentication (MFA) is causing issues

### 3. Check Account Status

In Active Directory:

- Locate the user account
- Check whether the account is locked
- Review account status and recent login attempts

### 4. Unlock the Account

If the account is locked:

- Unlock the account
- Advise the user of the likely cause (multiple failed login attempts)

### 5. Reset the Password

If required:

- Set a temporary password
- Enforce password change at next login if appropriate
- Communicate the temporary password securely

### 6. Check for Cached Credentials

If lockouts continue:

- Check mobile devices
- Check Outlook profiles
- Check mapped drives
- Check saved passwords in Credential Manager

Old credentials often cause repeated account lockouts.

### 7. Test Login

Ask the user to:

- Log out
- Log back in
- Access required systems
- Confirm access to email and Microsoft 365 services

### 8. Escalate If Required

Escalate if:

- Lockouts continue after password reset
- Multiple accounts are affected
- Directory services appear unavailable
- Security concerns are identified

## Resolution Confirmation

- Confirm successful login
- Confirm access to required applications
- Document actions taken
- Update and close the ticket
