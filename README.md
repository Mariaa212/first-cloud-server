# First Cloud Server with Ubuntu 22.04 and Nginx

## Project Overview
- Built a cloud server running Ubuntu 22.04 with Nginx hosting a simple HTML website.
- Why tho? Well, to practise Linux, SSH and basic cloud development.

## Tech Used
- Ubuntu 22.04 LTS
- Nginx
- AWS EC2 (free-tier)
- Git/GitHub

  ### Steps to Deploy

  1. Launch EC2 Instance:
      - Ubuntu 22.04 LTS
      - t3.micro
      - ED25519 key .pem
 
  2. SSH into the server:
      - ssh -i /c/aws-keys/my-first-key.pem ubuntu@13.60.56.106

  3. Update the System:
      - sudo apt update && sudo apt upgrade -y
    
  4. Install Nginx:
      - sudo apt install nginx -y
      - sudo systemctl start nginx
      - sudo systemctl enable nginx
    
  5. Deploy:
      - sudo nano /var/www/html/index.html
      - Paste HTML, save, refresh browser
    
  ### Website:

<img width="1920" height="980" alt="My-first-cloud-server-sc" src="https://github.com/user-attachments/assets/3fc86d2d-9d80-4d71-991a-9dc3b6353884" />

  ### Terminal:
  
<img width="697" height="481" alt="My-first-cloud-server-after-ssh-sc" src="https://github.com/user-attachments/assets/1b533a31-2f70-4d32-89bd-edbdeae8d27a" />

  ### What I learned:
    - Working with SSH and .pem keys.
    - Security group config for AWS.
    - Basic Linux commands (sudo, nano, systemctl)
    - How to check Nginx status.

     
     
