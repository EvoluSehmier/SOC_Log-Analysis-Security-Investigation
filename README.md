# Log Analysis Security Investigation

## 📌 Executive Summary
System logs revealed repeated failed login attempts indicating a possible brute-force attack.

## 🎯 Objective
Detect suspicious login behavior and assess risk.

## 🔍 Investigation

### Observations
- Multiple failed login attempts
- Attempts from same IP
- Activity during unusual hours

## 🚨 Indicators
- IP: 45.23.12.90
- Repeated login failures

## ⚖️ Risk Level
Medium → Potential account compromise

## ✅ Recommendations
- Enable account lockout
- Monitor IP activity

## 🧠 MITRE ATT&CK
- T1110 – Brute Force
