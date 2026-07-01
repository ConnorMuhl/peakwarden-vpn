# peakwarden-vpn
# A self-hosted WireGuard VPN. Built for privacy, owned entirely by me.
# What is peakwarden-vpn?
peakwarden-vpn is a personal, self-hosted VPN server built on WireGuard and deployed on a DigitalOcean droplet in San Francisco.
Unlike commercial VPN services, there is no third party involved -- no company logging traffic, no shared infrastructure, no subscription to a service I don't control. The server is mine, the keys are mine, and the tunnel is mine.
The goal is simple: I want my virtual environment to be a safe-room. Encrypted traffic, clean IP, and a private workspace for personal projects and sensitive work + anything else that benefits from not being exposed to a quasi public network.
# Why self-hosted?
Commercial VPNs require trusting a company with your traffic, and paying a subscription fee.  Self-hosting means the only entity that could ever see my data is me. For anyone serious about digital privacy and ownership of their own environment, that distinction matters.
# Stack
WireGuard -- modern, fast, minimal VPN protocol
Ubuntu 24.04 -- Server OS
DigitalOcean -- Cloud hosting ($4/month droplet, SFO2)
Windows Wireguard Client -- laptop side connection
# How it works
Your laptop connects to a WireGuard tunnel running on a private DigitalOcean server. All traffic is encrypted end-to-end and routed through the server before reaching the internet. Your real IP is replaced by the server's IP. Your ISP sees an encrypted connection, not your activity.
# Configuration
Example config files are in /config -- placeholders only, no real keys.
# Status
Active and running
# Screenshots
![IP Address Confirmed as SFO2 VPN](Docs/Screenshots/What_s_my_IP_Address_com_showing_SFO2.png)
![WireGuard Active Status](Docs/Screenshots/Wireguard_Dialgue_Box_Showing_Active_Status.png)
![Announcing the VPN Build](Docs/Screenshots/Announcing_to_Claude_what_we_re_vibecoding.png)
![DigitalOcean Droplet Dashboard](Docs/Screenshots/Digital_ocean_droplet_page.png)
![Nano Editor Open on Server](Docs/Screenshots/Nano_Editor_is_open.png)
# Built with:
Claude.
Vibecoded in one session.
