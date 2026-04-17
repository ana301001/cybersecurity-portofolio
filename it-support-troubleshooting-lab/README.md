# IT Support Troubleshooting Lab

## Overview
This project simulates real-world IT support scenarios where common system and network issues are identified, diagnosed, and resolved.

The goal is to demonstrate practical troubleshooting skills, root cause analysis, and structured problem-solving—key competencies in IT Support and Junior Cybersecurity roles.


## Scenario
An internal company environment is experiencing multiple IT issues reported by employees, including:

- Slow or no internet connectivity
- Website access failures
- System performance problems
- DNS resolution errors

The IT support team is responsible for identifying the root cause and restoring normal operations.

## Objectives
- Identify common IT and network issues
- Perform structured troubleshooting steps
- Demonstrate root cause analysis (RCA)
- Apply basic networking knowledge
- Document solutions clearly


## Step 1: Basic Network Setup
The simulated environment includes:
- Employee workstations
- Internal router
- DNS server
- Internal application server
- Internet gateway

## Step 2: Reported Issue (Case 1 – DNS Problem)

### Problem Description
Users report that they can access some websites, but internal company applications and certain external websites are not loading.

## Step 3: Troubleshooting Process

### 1. Initial Checks
- Verified network cable and Wi-Fi connection
- Confirmed IP address assignment
- Checked system connectivity using ping tests

### 2. DNS Investigation
- Tested domain resolution using nslookup
- Found inconsistent DNS responses

### 3. Root Cause Analysis
The issue was identified as a **misconfigured DNS server**, causing failures in domain name resolution.

## Step 4: Resolution
- Updated DNS configuration to correct server
- Flushed local DNS cache
- Restarted network services
- Verified connectivity restoration


## Result
After applying the fix:
- Websites loaded correctly
- Internal applications became accessible
- Network stability was restored

## Key Learning Outcomes
- DNS is critical for website access
- Small misconfigurations can cause major outages
- Structured troubleshooting prevents guesswork
- Verification after fixes is essential

## IT Support Skills Demonstrated
- Network troubleshooting
- DNS diagnostics
- Root cause analysis (RCA)
- System monitoring
- Documentation of technical issues

## Future Improvements
- Add Active Directory troubleshooting scenario
- Simulate hardware failure case
- Include ticketing system workflow (e.g. Service Desk process)
