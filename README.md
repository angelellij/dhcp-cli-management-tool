# DHCP CLI Management Tool (`dcmt`)

A lightweight CLI tool for managing **DHCP static ips** and generating ISC DHCP configuration on Linux systems.

## -------------------
## WORK IN PROGRESS !!
## -------------------

## Features
- Create new DHCP static ip (`dcmt add`)
- Update a static ip (replaces ip, dns or mac based on argument) (`dcmt update`)
- Search static ips (`dcmt search`)
- List static ips (`dcmt list`)
- Remove static ip (`dcmt remove`)
- Interactively create DHCP config (`dcmt create-conf`)

## Installation
Git clone this repo
```bash
git clone https://github.com/angelellij/dhcp-cli-management-tool
```

```bash
sudo apt install isc-dhcp-server #Dependencies
sudo chmod 755 dhcp-cli-management-tool/DEBIAN/postinst
dpkg-deb --build dhcp-cli-management-tool
sudo dpkg -i dhcp-cli-management-tool.deb
sudo chmod +x /usr/local/bin/dcmt
```

## Post-install
Create the isc-dhcp-server configuration that works with this repo
```bash
sudo dcmt create-conf
```
Add static ips with 
```bash
sudo dcmt add <ip> <mac> <dns>
```

## Disclaimer

I know a lot of folks do not aprove the use of AI. This project was made with it.

## License
MIT License
