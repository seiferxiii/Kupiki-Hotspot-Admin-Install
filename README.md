[![Slack](https://img.shields.io/badge/slack-kupiki--tools-blue.svg)](https://kupiki-tools.slack.com) ![Stars](https://img.shields.io/github/stars/kupiki/kupiki-hotspot-admin-install.svg?style=social&label=Star) [![Donate](https://img.shields.io/badge/%24-Donate-brightgreen.svg)](https://paypal.me/PiHomeServer)

What is Kupiki Hotspot Admin
==================

This application is a web frontend to monitor and administrate the [Kupiki Hotspot](https://github.com/pihomeserver/Kupiki-Hotspot-Script).

- Frontend application : [![Build Status](https://travis-ci.org/Kupiki/Kupiki-Hotspot-Admin-Frontend.svg?branch=master)](https://travis-ci.org/Kupiki/Kupiki-Hotspot-Admin-Frontend) ![npm dependencies](https://david-dm.org/Kupiki/Kupiki-Hotspot-Admin-Frontend.svg) [![Coverage Status](https://coveralls.io/repos/github/Kupiki/Kupiki-Hotspot-Admin-Frontend/badge.svg?branch=master)](https://coveralls.io/github/Kupiki/Kupiki-Hotspot-Admin-Frontend?branch=master) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/83b2ebb8ca3f46a9a2b08975ff714cd4)](https://www.codacy.com/app/pihomeserver/Kupiki-Hotspot-Admin-Frontend?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Kupiki/Kupiki-Hotspot-Admin-Frontend&amp;utm_campaign=Badge_Grade) [![Known Vulnerabilities](https://snyk.io/test/github/kupiki/kupiki-hotspot-admin-frontend/badge.svg)](https://snyk.io/test/github/kupiki/kupiki-hotspot-admin-frontend)
- Backend application : [![Build Status](https://travis-ci.org/Kupiki/Kupiki-Hotspot-Admin-Backend.svg?branch=master)](https://travis-ci.org/Kupiki/Kupiki-Hotspot-Admin-Backend) ![npm dependencies](https://david-dm.org/Kupiki/Kupiki-Hotspot-Admin-Backend.svg) [![Coverage Status](https://coveralls.io/repos/github/Kupiki/Kupiki-Hotspot-Admin-Backend/badge.svg?branch=master)](https://coveralls.io/github/Kupiki/Kupiki-Hotspot-Admin-Backend?branch=master) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/6fb5dbcf65184755ad36a97590b78fe2)](https://www.codacy.com/app/pihomeserver/Kupiki-Hotspot-Admin-Backend?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Kupiki/Kupiki-Hotspot-Admin-Backend&amp;utm_campaign=Badge_Grade)  [![Known Vulnerabilities](https://snyk.io/test/github/kupiki/kupiki-hotspot-admin-backend/badge.svg)](https://snyk.io/test/github/kupiki/kupiki-hotspot-admin-backend)


Warning
=====

The application is in development so be sure that you will find bugs and errors. So please log them in the [Frontend GitHub issues](https://github.com/Kupiki/Kupiki-Hotspot-Admin-Frontend/issues)
the  [Backend GitHub issues](https://github.com/Kupiki/Kupiki-Hotspot-Admin-Backend/issues), or current repo issues for installation issues.

Features
=======
- Monitoring
    - Display in a dashboard CPU, disk, memory, uptime and temperature (for Raspberry Pi)
    - OS System information
    - List of services with status
    - Netflow information (if installed)
- System administration
    - Stop / Start services
    - Upgrade system
    - Reboot / Shutdown system
- Hotspot administration
    - Change hotspot name
    - Update hostapd service configuration
- Hotspot management
    - Users management

How to install
=======

- Clone the project with the install script
```
git clone https://github.com/Kupiki/Kupiki-Hotspot-Admin-Install
```
- Run the installation script
```
chmod +x install_kupiki_admin.sh && ./install_kupiki_admin.sh
```
Screenshots
=======

#### Login screen
![login](http://www.pihomeserver.fr/hosting/kupiki/login.png)

#### Dashboard
![dashboard](http://www.pihomeserver.fr/hosting/kupiki/dashboard.png)

#### Basic configuration
![simple](http://www.pihomeserver.fr/hosting/kupiki/simple.png)

#### Advanced configuration
![advanced](http://www.pihomeserver.fr/hosting/kupiki/advanced.png)

#### Hotspot management
![mgmt](http://www.pihomeserver.fr/hosting/kupiki/mgmt.png)