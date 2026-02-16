# NGINX Site Manager

Interactive Bash CLI tool to enable/disable NGINX virtual hosts.

## Features

- Lists all sites from `/etc/nginx/sites-available`
- Shows enabled/disabled status
- Toggle sites interactively
- Reload NGINX with config test
- Color-coded UI

## Requirements

- NGINX installed
- sudo privileges

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/nginx-site-manager.git
cd nginx-site-manager
chmod +x nginx-site-manager
sudo cp nginx-site-manager /usr/local/bin/nginx-site-manager
