# cybersecurity-task4-elevate
Configured Windows Firewall to block Telnet (port 23) and allow SSH (port 22) as part of basic firewall setup.
# Task 4 - Firewall Configuration (Windows)

## Objective
Configure Windows Firewall to block inbound traffic on port 23 (Telnet) and allow port 22 (SSH). Understand how firewall rules filter network traffic.



## Steps Performed (Windows Only)

1. Opened Firewall Tool  
   - Used 'wf.msc' to open Windows Defender Firewall with Advanced Security

2. Listed Current Firewall Rules  
   - Viewed default and custom rules under Inbound Rules

3. Created a Rule to Block Port 23 (Telnet)  
   - Created a new inbound rule for TCP port 23  
   - Selected Block the connection

4. Tested the Rule  
   - Observed the rule listed and confirmed it was applied  

5. Created a Rule to Allow Port 22 (SSH)  
   - Though SSH is more relevant to Linux, added it to show understanding of rule-based control

6. Removed the Block Rule for Port 23  
   - Deleted the Telnet block rule to restore original firewall state

7. Documented GUI Steps Used  
   - This README explains each step taken via Windows Firewall GUI

8. Summary: How Firewall Filters Traffic  
   Firewalls inspect incoming and outgoing network packets. Based on configured rules, they either allow or block traffic by filtering based on ports, protocols, IP addresses, or applications. This enhances system security by controlling exposure to unauthorized access.



## Tools Used
- Windows Defender Firewall with Advanced Security

## Task Outcome
- Understood how to create, view, and remove basic firewall rules
- Learned how Windows Firewall filters network traffic using port-based rules
