# Wi-Fi Connectivity Issues

## Problem

A user reports they cannot connect to Wi-Fi or cannot access network resources while connected.

Common symptoms:

- Unable to join a wireless network
- Connected but no internet access
- Intermittent connection drops
- Slow network performance
- VPN not working over Wi-Fi

---

## Troubleshooting Process

### 1. Determine Scope

Ask:

- Is the issue affecting one user or multiple users?
- Are other devices able to connect?

This helps identify whether the issue is local to the user or affecting the wider network.

---

### 2. Check Wi-Fi Status

Confirm:

- Wi-Fi is enabled
- Airplane mode is disabled
- Correct wireless network is selected

---

### 3. Verify Signal Strength

Check:

- Distance from access point
- Physical obstructions
- Weak signal indicators

Poor signal strength can cause intermittent connectivity issues.

---

### 4. Forget and Reconnect

Steps:

1. Forget the wireless network.
2. Reconnect using the correct password.
3. Test connectivity.

This can resolve corrupted network profiles.

---

### 5. Check IP Address

Verify the device has received a valid IP address.

Windows:

```cmd
ipconfig
```

Look for:

- Valid IPv4 address
- Default gateway
- DNS servers

An invalid address may indicate a DHCP issue.

---

### 6. Test Network Access

Determine what is actually failing.

Questions:

- Can the user access websites?
- Can they access company resources?
- Can they access shared drives?
- Is the issue internet access or network access?

---

### 7. Test Another Device

Check whether:

- Phone can connect
- Another laptop can connect

This helps determine whether the problem is device-specific.

---

### 8. Restart Network Equipment

If appropriate:

- Restart router
- Restart access point
- Restart device

Many temporary connectivity issues are resolved by restarting equipment.

---

## Common Causes

### Incorrect Password

Symptoms:

- Authentication failures
- Unable to join network

---

### DHCP Issues

Symptoms:

- Connected but no internet
- Invalid IP address

---

### DNS Issues

Symptoms:

- Websites unavailable
- Network appears connected

Users may still be able to reach services via IP address.

---

### Weak Signal

Symptoms:

- Slow speeds
- Random disconnections
- Poor call quality

---

### Access Point Failure

Symptoms:

- Multiple users affected
- Entire area loses connectivity

Usually requires escalation.

---

## Escalation Criteria

Escalate if:

- Multiple users are affected
- Access point appears offline
- DHCP services are unavailable
- Network infrastructure issues are suspected
- Hardware replacement may be required

---

## Interview Scenario

### User Reports

"My Wi-Fi isn't working."

Good response:

> First I'd determine whether the issue affects only that user or multiple users. I'd then check whether the device is connected to the correct wireless network, verify signal strength, confirm it has received a valid IP address, and identify whether the issue is Wi-Fi connectivity, internet access, or access to a specific service.

---

## Interview Summary

A strong 1st line explanation:

> When troubleshooting Wi-Fi issues, I would first determine the scope of the problem, verify connectivity and network settings, check for a valid IP address, test whether the issue affects other devices, and identify whether the root cause is authentication, DHCP, DNS, signal strength, or wider network infrastructure.
