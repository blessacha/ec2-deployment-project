Project 1 – EC2 Deployment
Cloud Engineering Practice | AWS | Windows EC2 | IIS Web Server
🚀 Overview

This project marks the first step in my cloud engineering journey.
I deployed a Windows-based EC2 instance, installed IIS Web Server, and hosted a simple HTML webpage.

✅ Steps I Completed
1. Launched an EC2 Instance
Chose Windows Server 2019
Selected a key pair (.pem)
Configured security group:
Allowed RDP (3389)
Allowed HTTP (80)

2. Connected via Remote Desktop
Used RDP Client on Windows
Retrieved the Administrator password from AWS using the .pem key
Logged into the server

3. Installed IIS Web Server
Inside the EC2 Windows instance:
Opened Server Manager!
  Added role: Web Server (IIS)

4. Uploaded My Website
  Navigated to the web root:
  "C:\inetpub\wwwroot\"
Replaced the default file with my index.html
Confirmed the website loaded using my EC2 Public IP

5. Final Result
Below is a screenshot of the deployed site:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1ef1e1d8-f3b9-4b85-9d58-9da7369e88c6" />



![photo_2025-11-14_20-57-24](https://github.com/user-attachments/assets/5d41104c-37db-4301-a67a-b56fa365a49d)
