# VPS Fullstack Infrastructure Project

Live demo:
https://taavitoomsalu.com

## Overview

Small self-hosted web stack deployed on a Linux VPS.

The goal of the project was to learn:
- Linux server administration
- reverse proxy configuration
- service management
- HTTPS setup
- basic infrastructure troubleshooting

## Stack

- Debian VPS
- Nginx
- Node.js + Express
- systemd
- Let's Encrypt SSL
- Git + GitHub

## Architecture

Browser
↓
Nginx (reverse proxy)
↓
Node.js API (localhost:3000)

Static frontend is served directly by Nginx.

## Features

- HTTPS enabled
- Reverse proxy configuration
- API endpoint (`/api/health`)
- systemd-managed backend service
- Firewall configuration (UFW)
- SSH key authentication

## Troubleshooting / Debugging

Worked through:
- nginx upstream connection issues
- missing Node dependencies# VPS Fullstack Infrastructure Project

Live demo:
https://taavitoomsalu.com

## Overview

Small self-hosted web stack deployed on a Linux VPS.

The goal of the project was to learn:
- Linux server administration
- reverse proxy configuration
- service management
- HTTPS setup
- basic infrastructure troubleshooting

## Stack

- Debian VPS
- Nginx
- Node.js + Express
- systemd
- Let's Encrypt SSL
- Git + GitHub

## Architecture

Browser
↓
Nginx (reverse proxy)
↓
Node.js API (localhost:3000)

Static frontend is served directly by Nginx.

## Features

- HTTPS enabled
- Reverse proxy configuration
- API endpoint (`/api/health`)
- systemd-managed backend service
- Firewall configuration (UFW)
- SSH key authentication

## Troubleshooting / Debugging

Worked through:
- nginx upstream connection issues
- missing Node dependencies
- service restart loops
- port conflicts between PM2 and systemd
- firewall configuration problems

## What I learned

- Linux server management
- Nginx configuration
- systemd service setup
- log inspection using journalctl and nginx logs
- debugging service failures and networking issues
- service restart loops
- port conflicts between PM2 and systemd
- firewall configuration problems

## What I learned

- Linux server management
- Nginx configuration
- systemd service setup
- log inspection using journalctl and nginx logs
- debugging service failures and networking issues
