# WireGuard VPN Deployment

## Overview
This project demonstrates deploying a secure VPN using WireGuard on a cloud VM.

## What I Did
- Installed WireGuard on Ubuntu EC2 instance
- Generated public/private key pairs
- Configured VPN interface (wg0)
- Started encrypted tunnel on port 51820

## Tools Used
- WireGuard
- Linux (Ubuntu)
- AWS EC2


## Key Takeaways
- Secure VPN setup
- Network interface configuration
- Encryption-based communication# WireGuard VPN Deployment

- ## How to Connect (Demo)

1. Install WireGuard
2. Use the following config:

[Interface]
PrivateKey = (client key)

[Peer]
PublicKey = (server public key)
Endpoint = 51.20.18.204:51820
AllowedIPs = 10.0.0.0/24

iguration
- Encryption-based communication
