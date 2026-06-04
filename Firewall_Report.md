# Firewall Configuration Report

## Task Title

Setup and Use a Firewall on Windows/Linux

## Objective

The objective of this task is to learn how to configure and manage firewall rules to control network traffic. This task demonstrates how a firewall can be used to block or allow specific ports and improve system security.

## Tools Used

* Windows Defender Firewall with Advanced Security (Windows)
* UFW (Uncomplicated Firewall) on Linux (Optional)
* Command Prompt / Terminal

## Introduction

A firewall is a network security system that monitors and filters incoming and outgoing traffic based on predefined security rules. Firewalls help protect computers and networks from unauthorized access, malware, and other cyber threats.

## Procedure

### Step 1: Open Firewall Configuration

Opened Windows Defender Firewall with Advanced Security using the Run command:

```cmd
wf.msc
```

### Step 2: View Existing Rules

Navigated to Inbound Rules and reviewed the existing firewall configuration.

### Step 3: Create a Rule to Block Port 23

Created a new inbound rule to block TCP Port 23 (Telnet).

Configuration:

* Rule Type: Port
* Protocol: TCP
* Port Number: 23
* Action: Block the Connection
* Profile: Domain, Private, Public
* Rule Name: Block Telnet Port 23

### Step 4: Test the Rule

Verified that the firewall rule was successfully added and active. Network testing tools and firewall rule lists were used to confirm the configuration.

### Step 5: Remove the Rule

Deleted the test rule after verification to restore the original firewall settings.

## Screenshots

The following screenshots are included in the repository:

1. Firewall Console Opened
2. Existing Inbound Rules
3. Creation of Block Port 23 Rule
4. Verification/Test Results
5. Deletion of Firewall Rule

## Results

Successfully configured a firewall rule to block inbound traffic on Port 23. The rule was verified and later removed without affecting the system's normal operation.

## Learning Outcomes

* Understood the purpose of firewalls in network security.
* Learned the difference between inbound and outbound rules.
* Gained experience creating and deleting firewall rules.
* Learned why Telnet (Port 23) is considered insecure.
* Understood how traffic filtering improves security.

## Conclusion

This task provided practical experience in firewall management and network security. By creating, testing, and removing firewall rules, a better understanding of traffic filtering and system protection was achieved. Firewalls play a critical role in preventing unauthorized access and securing computer systems from network-based threats.
