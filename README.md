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
```

## Running as root

```bash
sudo /usr/local/bin/nginx-site-manager
```

## Example interface

```bash
=======================================
              NGINX Sites              
        select number to toggle        
=======================================
[1] ● site1
[2] ● site2
[3] ● site3
[4] ○ site4
[5] ● site5
[6] ○ site6
[7] ○ site7
[8] ● site8
[9] ● site9
=======================================
[r] Reload NGINX  [q] Quit
=======================================
Choice: 
```

## Legend

| Symbol | Meaning |
| --- | --- |
|● | Site enabled |
|○ | Site disabled |

## Usage

Enter a number → Toggle site state
``r`` → Test configuration and reload NGINX
``q`` → Exit program
