# ubuntu-script
Initial script for Ubuntu Server


# Server Setup Script

This repository contains a Bash script that automates the initial setup of a server, including the installation of essential packages, security tools, databases, and a Python environment for Flask applications.

## Features

- Updates the system and installs essential dependencies.
- Configures the firewall using UFW (Uncomplicated Firewall) and Fail2Ban.
- Installs and configures CSF (ConfigServer Security & Firewall).
- Allows the creation of a new admin user.
- Installs Docker and Docker Compose.
- Configures the timezone.
- Installs databases (PostgreSQL, MySQL, and Redis) inside Docker containers.
- Sets up a Python virtual environment for Flask applications and installs Flask.

## Prerequisites

Before running the script, ensure that you have:

- Root access or sudo permissions to execute installation commands.
- A Debian/Ubuntu-based operating system.

## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/mikusher/ubuntu-script.git
   cd ubuntu-script```


2. Give execution permission to the script:
   ```bash
   chmod +x setup_script.sh```
   

3. Execute the script:
  ```bash
   sudo setup_script.sh```
