# Helium

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

Helium is a dnsmasq installer autoscript. Helium will setup dnsmasq to block ads, tracker, malware, phishing, porn and many more.
  
<p align="center">
  <img src="5C0C4775-1FF4-4373-94B0-DCA1EF151752.png">
</p>

It helps you manage dnsmasq configuration by simply following the on-screen instructions as easy as 1, 2, 3, y or n.

<p align="center">
  <img src="91B9BC35-5AD1-4274-81B7-021FDBFCF7F2.png">
</p>

requirement : Debian/Ubuntu VPS

To install, copy paste this command:

```
rm -rf /usr/local/sbin/helium && wget -q -O /usr/local/sbin/helium https://raw.githubusercontent.com/abidarwish/helium/main/helium.sh && chmod +x /usr/local/sbin/helium && helium
```
