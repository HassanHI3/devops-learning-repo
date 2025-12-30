# Domain + EC2 + DNS (NGINX)

## Overview
This lab demonstrates hosting a web server on AWS EC2 and connecting it to a custom domain using DNS.

## Architecture
Browser → DNS (Cloudflare) → EC2 Public IP → NGINX (Port 80)

## What I Built
- Purchased and configured a custom domain
- Deployed an EC2 instance on AWS
- Installed and ran NGINX
- Opened required network ports (22, 80)
- Created DNS A records pointing the domain to the EC2 instance

## What I Learned
- How DNS A records resolve domains to IP addresses
- How EC2 security groups control inbound traffic
- How HTTP traffic flows over port 80
- How to host a basic web server on AWS

## Evidence
Screenshots are available in the `screenshots/` directory.

