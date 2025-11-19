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
      - ssh -i/path/to/key.pem.ubuntu@PUBLIC_IP

  3. Update the System:
      - sudo apt update && sudo apt upgrade -y
    
  4. Start and Enable Nginx:
      - sudo systemctl start nginx
      - sudo systemctl enable nginx
