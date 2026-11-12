# Raspberry-Pi-NAS-Server
Project Overview

This project documents the deployment and configuration of a Network Attached Storage (NAS) server using a Raspberry Pi and a 1TB external SSD.

The NAS provides centralised file storage accessible from both Linux and Windows devices across a local network. Remote access is supported through a WireGuard VPN hosted on an OPNsense firewall.

The project demonstrates Linux system administration, storage management, network file sharing, firewall configuration and secure remote connectivity.

## Hardware Setup

<h2>Hardware Setup & Project Documentation</h2>

<table>
<tr>
<td width="55%" valign="top">

<h3>Project Documentation</h3>

<ol>
<li><a href="docs/01-SSD-Preparation.md">SSD Preparation</a></li>
<li><a href="docs/02-Raspberry-Pi-Storage-Mounting.md">Raspberry Pi Storage Mounting</a></li>
<li><a href="docs/03-Samba-Configuration.md">Samba Configuration</a></li>
<li><a href="docs/04-Linux-Client-Access.md">Linux Client Access</a></li>
<li><a href="docs/05-Windows-Client-Access.md">Windows Client Access</a></li>
<li><a href="docs/06-OPNsense-and-WireGuard-Configuration.md">OPNsense and WireGuard Configuration</a></li>
</ol>

</td>
<td width="45%" align="center" valign="top">
<img src="screenshots/PiSetup.jpg" alt="Raspberry Pi NAS hardware" width="300">
</td>
</tr>
</table>

## Hardware and Software

| Component | Description |
|---|---|
| NAS Server | Raspberry Pi |
| Operating System | Raspberry Pi OS |
| Storage | 1TB External SSD |
| Filesystem | ext4 |
| File Sharing | Samba (SMB) |
| Firewall / Router | OPNsense |
| VPN | WireGuard |
| Linux Client | CachyOS |
| Windows Client | Windows 11 |
