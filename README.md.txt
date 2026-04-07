# SOC Incident Response Simulation Project

## Objective
To simulate real-world incident response actions after detecting a security incident.

## Tools Used
- Splunk Enterprise

## Scenario
A brute force attack was detected from IP address 192.168.1.10, where multiple failed login attempts were followed by a successful login.

## Incident Identification
- Repeated failed login attempts observed
- Suspicious IP address identified
- Possible account compromise detected

## Response Actions

### 1. Identification
- Analyzed logs using SIEM tool
- Confirmed brute force attack pattern

### 2. Containment
- Blocked suspicious IP address
- Disabled compromised user account

### 3. Eradication
- Reset passwords for affected accounts
- Removed unauthorized access

### 4. Recovery
- Restored system functionality
- Monitored for further suspicious activity

### 5. Lessons Learned
- Enforce strong password policies
- Enable multi-factor authentication
- Improve monitoring and alerting

## Risk Level
Critical

## Impact
- Unauthorized access to system
- Potential data breach
- Compromise of user accounts

## Conclusion
Effective incident response minimizes damage and ensures faster recovery from security incidents.
