# AWS Cloud Firewall Configuration using EC2

## Aim
To configure cloud firewall rules using AWS Security Groups to control network access to an EC2 instance.

---

## Requirements
- AWS Account
- Amazon EC2 Instance
- Security Groups
- Ubuntu Server
- Internet Browser

---

## Procedure
1. Login to AWS Management Console.
2. Open EC2 Dashboard.
3. Launch or select an EC2 instance.
4. Configure Security Group inbound rules.
5. Allow SSH access on Port 22.
6. Allow HTTP access on Port 80.
7. Connect to the instance.
8. Install Apache Web Server.
9. Create a test webpage.
10. Access the webpage using the Public IP address.

---

## EC2 Instance Running

![Instance Running](instance-running.png)

---

## Security Group Firewall Rules

HTTP (Port 80) and SSH (Port 22) are allowed.

![Security Group Rules](security-group-rules.png)

---

## Website Accessible when HTTP Port 80 is Allowed

The webpage loads successfully when the firewall allows HTTP traffic.

![Website Working](website-working.png)

---

## Website Blocked when HTTP Port 80 is Removed

When the HTTP rule is removed from the firewall, the website becomes inaccessible.

![Website Blocked](website-blocked.png)

---

## Result
Cloud firewall rules were successfully configured and tested using AWS EC2 Security Groups.
