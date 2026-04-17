# Risk Assessment Project – Internal Company IT System

## Overview
This project presents a structured risk assessment for a hypothetical company’s internal IT system. It follows basic Governance, Risk, and Compliance (GRC) principles to identify risks, evaluate their severity, and propose mitigation controls.


## Business Scenario
A mid-sized company uses an internal system that supports:

- Employee authentication and login
- File storage and document sharing
- Internal communication and workflows
- Access to sensitive business data

The system must remain:
- Secure
- Available
- Reliable
- Compliant with internal security policies

## Objectives
- Identify key information security risks
- Assess likelihood and business impact
- Classify risks using a risk matrix
- Propose realistic security controls
- Demonstrate GRC-style structured thinking


## Step 1: Asset Identification

| Asset ID | Asset Name              | Description |
|----------|------------------------|-------------|
| A1       | User Accounts          | Employee login credentials |
| A2       | Internal Database      | Stores company data |
| A3       | File Sharing System    | Internal document storage |
| A4       | Email System           | Internal communication |
| A5       | IT Infrastructure     | Servers, network, endpoints |

📸 Screenshot:
Add simple table view here → `asset-register.png`


##  Step 2: Risk Identification

| Risk ID | Risk Description |
|--------|------------------|
| R1 | Phishing attacks targeting employees |
| R2 | Malware infection via email or downloads |
| R3 | Unauthorized access to internal systems |
| R4 | Data leakage due to weak access control |
| R5 | System downtime due to server failure |
| R6 | Weak password practices by users |


## Step 3: Risk Analysis

### Risk Scoring Method
- Likelihood: Low / Medium / High
- Impact: Low / Medium / High
- Risk Level = combination of both


| Risk | Likelihood | Impact | Risk Level | Explanation |
|------|-----------|--------|-----------|-------------|
| R1 | High | High | Critical | Phishing is common and targets users directly |
| R2 | Medium | High | High | Malware can spread via attachments or downloads |
| R3 | Medium | High | High | Weak authentication increases breach risk |
| R4 | Medium | High | High | Poor access control exposes sensitive data |
| R5 | Low | High | Medium | Rare but impactful system outage |
| R6 | High | Medium | High | Weak passwords are a common vulnerability |


## Step 4: Risk Matrix

Create a 3x3 or 5x5 matrix:

- X-axis: Likelihood
- Y-axis: Impact

Place risks like this:
- R1 → Critical zone
- R2, R3, R4, R6 → High zone
- R5 → Medium zone

Screenshot:
Save as `risk-matrix.png`

Build using:
- :contentReference[oaicite:0]{index=0} or  
- :contentReference[oaicite:1]{index=1}  


## Step 5: Mitigation Strategies

| Risk | Mitigation Controls | Type |
|------|--------------------|------|
| R1 | Security awareness training, email filtering, MFA | Preventive |
| R2 | Antivirus, endpoint detection, secure downloads | Preventive |
| R3 | Role-based access control (RBAC), MFA | Preventive |
| R4 | Data classification, access audits | Detective |
| R5 | Backup systems, redundancy, disaster recovery plan | Corrective |
| R6 | Password policy enforcement, MFA | Preventive |

📸 Screenshot:
Save as `mitigation-table.png`


## Step 6: Key Risk Findings
The most critical risks identified are:

- Phishing attacks (R1)
- Weak password practices (R6)
- Unauthorized access (R3)

These risks are primarily user-related, highlighting that human behavior is one of the biggest security weaknesses in an organization.


## Step 7: Recommendations
To improve the overall security posture:
- Implement multi-factor authentication (MFA)
- Conduct regular cybersecurity awareness training
- Enforce strong password policies
- Introduce role-based access control (RBAC)
- Improve monitoring and logging systems


## Key Takeaways
- Risk management is about prioritization, not just detection
- Human behavior is a major security risk factor
- Technical controls must be combined with awareness and policy
- Structured thinking is essential in GRC roles


##  Future Improvements
- Align with ISO 27001 framework
- Add quantitative risk scoring (numerical model)
- Simulate real SIEM alerts
- Expand into continuous risk monitoring model
