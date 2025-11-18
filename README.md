# DHCP Reservation Tool (`drt`)

A lightweight CLI tool for managing **DHCP reservations** and generating ISC DHCP configuration on Linux systems.

## -------------------
## WORK IN PROGRESS !!
## -------------------

## Features
- Create new DHCP reservations (`drt new`)
- Append additional MAC addresses to a reservation (`drt add`)
- Remove MAC address from a reservation (`drt pop`)
- Update a reservation (replaces ip, dns or mac based on argument) (`drt update`)
- Search reservations (`drt search`)
- List reservations (`drt list`)
- Remove reservation (`drt delete`)
- Interactively create DHCP config (`drt create-conf`)

## Installation
```bash
dpkg-deb --build dhcp-reservation-tool
sudo dpkg -i dhcp-reservation-tool.deb
```

## Disclaimer

I know a lot of folks do not aprove the use of AI. This project was made with it.

## License
MIT License
