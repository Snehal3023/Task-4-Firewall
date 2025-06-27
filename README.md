# Task-4-Firewall
Configure and test basic firewall rules to allow or block traffic.
### 1. To open Firewall Configuration Tool
Press Windows + R, type firewall.cpl, press Enter.

Click Advanced settings on the left.

### 2. Current Rules
![rule](https://github.com/user-attachments/assets/cf6062d3-ceed-4631-9839-dfcf264c8501)

### Add a rule to block inbound traffic on a specific port 
#### Steps to block specific port

1. In Inbound Rules, click New Rule…

2. Select Port, click Next.

3. Select TCP, enter 23.

4. Click Block the connection, then click Next.

5. Check all profiles (Domain, Private, Public), click Next.

6. Name it: Block Telnet Port 23, then Finish.


### Test the rule by attempting to connect to that port locally or remotely
Step 1: Enable Telnet Client
Install Telnet Client

Step 2: Open Command Prompt (cmd) as Administrator.
telnet 127.0.0.1 23

![test connection](https://github.com/user-attachments/assets/31cf33c8-15d1-4413-abc5-9616839b9457)


### Remove the Test Rule
In Inbound Rules, find Block Telnet Port 23, right-click → Delete.

### Summary
Port:-23

Protocol:- TCP

IP:- 127.0.0.1 23

