# Basics - Network / Hosts Configuration

This repository contains tasks and scripts related to basic networking concepts, including managing the `/etc/hosts` file and modifying host resolutions on Linux.

## Tasks

### 0. Change your home IP
* **File:** `0-change_your_home_IP`
* **Description:** A Bash script that automatically updates the `/etc/hosts` file on an Ubuntu server to meet the following requirements:
  * `localhost` resolves to `127.0.0.2`
  * `facebook.com` resolves to `8.8.8.8`

#### Usage:
1. Make the script executable:
   ```bash
   chmod +x 0-change_your_home_IP
