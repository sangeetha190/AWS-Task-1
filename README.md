
# Task: Create a Windows VM in AWS, Connect via RDP & Retrieve System Info
## Step 1: Launch a Windows EC2 Instance
   - Log in to AWS Console using IAM or Root account.
   - Go to EC2 Dashboard → Click Launch Instance.
   - Choose Microsoft Windows Server as the AMI.
   - Select Instance Type (e.g., t2.micro for free tier).
   - Configure Key Pair for authentication.
   - Enable RDP (Port 3389) in Security Group settings.
   - Click Launch and wait for the instance to start.

## Step 2: Connect to Windows VM via RDP
   - Go to AWS EC2 Dashboard → Select the instance.
   - Click "Connect" → Choose RDP Client.
   - Click "Get Password" (use the key pair file to decrypt).
   - Copy the Public IP Address of the instance.
   - Open Remote Desktop Connection (mstsc) on your laptop.
   - Enter the Public IP, Administrator username, and Password.
   - Click Connect to access the Windows VM.
   - After successfully connected.
## Step 3: Retrieve System Information
   - Once inside the Windows VM, open Command Prompt:
   - Press Win + R, type cmd, and press Enter.
   - Run the following command to get system details:
   - ## systeminfo
   - Wait for the output to display system information.
## Step 4: Save System Info to a File
   - Run the command to save output
   - ## systeminfo > C:\Users\Administrator\Desktop\systeminfo.txt
   - The file systeminfo.txt will be created on the desktop.

![Screenshot 2025-03-04 235527](https://github.com/user-attachments/assets/83fb9f2d-475e-48bf-bbbb-4989604d9ed0)
## ✅ Task Completed!
- Successfully created a Windows VM in AWS.
- Connected via Remote Desktop (RDP).
- Retrieved and saved system information.
- Attached the systeminfo.txt file for verification.
