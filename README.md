# Raspberry-Pi-NAS-Server
Project Overview

This project documents the deployment and configuration of a Network Attached Storage (NAS) server using a Raspberry Pi and a 1TB external SSD.

The NAS provides centralised file storage accessible from both Linux and Windows devices across a local network. Remote access is supported through a WireGuard VPN hosted on an OPNsense firewall.

The project demonstrates Linux system administration, storage management, network file sharing, firewall configuration and secure remote connectivity.

Hardware and Software

Component

Description

NAS Server

Raspberry Pi

Operating System

Raspberry Pi OS

Storage

1TB External SSD

Filesystem

ext4

File Sharing

Samba (SMB)

Firewall / Router

OPNsense

VPN

WireGuard

Linux Client

CachyOS

Windows Client

Windows 11

Network Configuration

Component

IP Address

Home Network

192.168.1.0/24

Raspberry Pi NAS

192.168.1.175

WireGuard Network

10.10.10.0/24

SMB Port

TCP 445

Project Documentation

Project Overview

Hardware and Network Setup

SSD Preparation

Storage Mounting

Samba Configuration

Linux Client Access

Windows Client Access

WireGuard Remote Access

Security and Firewall Rules

Security Considerations

Samba shares require authenticated user access.

Guest access is disabled.

Remote NAS access is provided through WireGuard.

SMB traffic uses TCP port 445 and is not exposed directly to the public internet.

OPNsense firewall rules control access from VPN clients.

The NAS uses a DHCP reservation to maintain a consistent local IP address.
