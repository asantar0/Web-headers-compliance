# Web headers compliance
Welcome! This repository is dedicated to enhancing headers in webpages. 

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [License](#license)
- [Disclaimer](#disclaimer)

### Installation
1. Copy the file /etc/nginx/includes/custom-headers.conf in your NGINX folder.
2. Add the line "include includes/custom-headers.conf;" from the file /etc/nginx/sites-available/example.com.conf.
3. Reload nginx service with "systemctl reload nginx".

### License
This project is licensed under the MIT License. See the LICENSE file for more details.

### Disclaimer
This project is provided as-is, and the authors are not responsible for any damages or losses resulting from its use. Always test security measures in a staging environment before applying them to a prod site.
