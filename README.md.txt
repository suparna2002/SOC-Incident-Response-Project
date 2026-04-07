# SOC Incident Response Simulation Project

## Objective
To simulate how a Security Operations Center (SOC) responds to a detected security incident.

## Scenario
Multiple failed login attempts were detected from IP address 192.168.1.10, followed by a successful login.

## Incident Identification
- Repeated failed login attempts observed
- Suspicious IP: 192.168.1.10
- Possible brute force attack detected

## Incident Response Steps

### 1. Identification
- Logs were analyzed using SIEM tool
- Suspicious activity was detected

### 2. Containment
- Block the suspicious IP address
- Disable compromised user account

### 3. Eradication
- Remove malicious access
- Reset passwords for affected accounts

### 4. Recovery
- Restore system to normal state
- Monitor for further suspicious activity

### 5. Lessons Learned
- Implement strong password policy
- Enable multi-factor authentication
- Improve monitoring and alerting

## Conclusion
Proper incident response helps minimize damage and ensures quick recovery from security incidents.