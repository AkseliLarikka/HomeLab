# Homelab Documentation

This repository documents the setup and configuration of my homelab using Raspberry Pi devices. The goal is to host a personal website, experiment with a Minecraft server, and implement security monitoring using Wazuh and ClamAV.

## Table of Contents

1. [Introduction](#introduction)
2. [Hardware](#hardware)
3. [Network Configuration](#network-configuration)
4. [Web Server Setup](#web-server-setup)
5. [Minecraft Server](#minecraft-server)
6. [Security Monitoring](#security-monitoring)
7. [Future Improvements](#future-improvements)

## Introduction

The purpose of this homelab is to learn and experiment with various technologies while maintaining a secure and efficient network environment.

## Hardware

- Raspberry Pi 3B+
- Raspberry Pi 5
- TP-Link router
    - Model: cheapest possible
- PC for remote access

## Network Configuration

- Assigned static IP addresses to both Raspberry Pis.
- Configured SSH for remote access.
- Set up hostnames for easy identification.

## Web Server Setup

- Installed Apache on Raspberry Pi 3B+.
- Hosted a personal website in `/var/www/html`.

## Minecraft Server

- Installed Java and set up a Minecraft server on Raspberry Pi 5.
- Configured server properties for experimental purposes.

## Security Monitoring

- Installed Wazuh agent on both Raspberry Pis for security monitoring.
- Configured ClamAV for regular antivirus scans.

## Future Improvements

- Expand the web server to be accessible from the public internet.
- Implement additional security measures.
- Explore containerization using Docker.

## Contributing

Feel free to fork this repository and contribute your own configurations and improvements.

## License

This project is licensed under the MIT License.
