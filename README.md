# DHCP CLI Management Tool (`drt`)

A lightweight CLI tool for managing **DHCP static ips** and generating ISC DHCP configuration on Linux systems.

## -------------------
## WORK IN PROGRESS !!
## -------------------

## Features
- Create new DHCP static ip (`drt add`)
- Update a static ip (replaces ip, dns or mac based on argument) (`drt update`)
- Search static ips (`drt search`)
- List static ips (`drt list`)
- Remove static ip (`drt remove`)
- Interactively create DHCP config (`drt create-conf`)

## Installation
```bash
sudo chmod 755 dhcp-cli-management-tool/DEBIAN/postinst
dpkg-deb --build dhcp-cli-management-tool
sudo dpkg -i dhcp-cli-management-tool.deb
sudo chmod +x /usr/local/bin/drt
```

## Disclaimer

I know a lot of folks do not aprove the use of AI. This project was made with it.

## License
MIT License
