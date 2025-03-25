# aws-networking

## Overview
This project demonstrates how to set up a Virtual Private Cloud (VPC) with private and public subnets across multiple availability zones, configure a NAT Gateway, and implement Security Groups and NACLs for traffic control.

## Setup Steps
1. VPC Creation: Configured using AWS Console.
2. Subnet Configuration: Public & Private subnets in different Availability Zones.
3. NAT Gateway: Enables private subnet instances to access the internet.
4. Security Groups & NACLs: Restrict inbound/outbound traffic as per best practices.
5. Testing: Verify connectivity via `ping` and SSH access via VScode

## Testing & Validation
- Run the following from a **private EC2 instance**:
  ```bash
  ping 8.8.8.8  # Verify internet connectivity
  curl https://aws.amazon.com  # Test HTTP requests

  ## Screenshots 
