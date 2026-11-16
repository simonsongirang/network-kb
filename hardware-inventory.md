# Hardware Inventory

## Hardware 1 — pihole

- **Model:** Raspberry Pi Model B Rev 2
- **Purpose:** Hosts Pi-hole for all local computers. Blocks ads and functions as the local DNS server.
- **Operating system:** Raspbian
- **Local DNS:** `pihole.local`
- **Private IP:** `10.88.111.12`

## Hardware 2 — vpn

- **Model:** Raspberry Pi 3 Model B Plus Rev 1.3
- **Purpose:** Hosts VPN (via wiregaurd) and tailscale connection.
- **Operating system:** Debian Bookworm
- **Local DNS:** vpn.local
- **Private IP:** 10.88.111.4

## Hardware 3 — mainframe

- **CPU:** Intel(R) Core(TM) i5-6600K CPU @ 3.50GHz
- **RAM:** 8GB DDR4 2400 MT/s
- **Purpose:** Hosts all sort of things.
- **Operating system:** Ubuntu 24
- **Local DNS:** mainframe.local
- **Private IP:** 10.88.111.24