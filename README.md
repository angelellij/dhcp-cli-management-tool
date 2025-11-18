# DHCP Reservation Tool (`drt`)

A lightweight CLI tool for managing **DHCP reservations** and generating ISC DHCP configuration on Linux systems.


## Features
- Create new DHCP reservations (`drt new`)
- Append additional MAC addresses to a reservation (`drt add`)
- Remove MAC from reservation (`drt delete`)
- Update DNS name from reservation (`drt update-dns`)
- Update IP in a reservation (`drt update-ip`)
- Replace all MACs from a reservation with a new one (`drt update-mac`)
- Search reservations (`drt search`)
- List reservations (`drt list`)
- Remove reservation (`drt remove`)
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
