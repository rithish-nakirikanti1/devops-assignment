# AWS DevOps Engineer Intern Assignment

## Candidate Details

- Name: Rithish Kumar Nakirikanti
- College: Malla reddy university
- Branch: Artificial Intelligence & Machine Learning
- Email: rithishnakirikanti720@gmail.com
---

## Objective

Deploy a simple website on an AWS EC2 Ubuntu instance using Nginx and document the deployment process.

---

# AWS Services Used

- Amazon EC2
- Security Groups

---

# EC2 Setup

1. Logged in to the AWS Management Console.
2. Launched an Ubuntu EC2 instance.
3. Created a Security Group.
4. Allowed the following inbound rules:
   - SSH (Port 22)
   - HTTP (Port 80)
5. Connected to the EC2 instance using SSH.

Example:
ssh -i your-key.pem ubuntu@13.207.204.159

# Linux Commands Used

## Update Package
sudo apt update
sudo apt upgrade -y
## Install Nginx
sudo apt install nginx -y
## Check Nginx Status
sudo systemctl status nginx
## Restart Nginx
sudo systemctl restart nginx
## Check Disk Usage
df -h
## Check Memory Usage
free -h
## Check Running Processes
ps -ef
## docker installed
sudo apt install docker.io -y
docker run hello-world

# Website Deployment

1. Removed the default Nginx page.
sudo rm /var/www/html/index.nginx-debian.html
2. Created a new HTML page.
sudo nano /var/www/html/index.html
3. Added personal information to the HTML page.
4. Restarted Nginx.
sudo systemctl restart nginx
# Website URL
http://13.207.204.159

# Screenshots Included

- EC2 Dashboard
- SSH Login
- Nginx Installation
- Nginx Running Status
- Website in Browser


# Learning Outcomes
- Created an AWS EC2 instance.
- Configured Security Groups.
- Connected to Linux using SSH.
- Installed and managed Nginx.
- Hosted a static website.
- Used Git and GitHub for version control.
- Docker installed and run hello world 
