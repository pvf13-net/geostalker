
# GeoStalker

A lightweight, zero-dependency bash tool that instantly reveals public geolocation and network details for any IP addresses.

Works perfectly in restricted environments (web terminals, sandboxes, Docker containers).

```bash
geostalk              # shows your current public IP + location
geostalk 8.8.8.8      # shows location of any public IP
geostalk -h           # help
```

### Features

- Real-time public IP detection
- City, region, country
- ISP / organization
- Latitude & longitude
- Timezone
- Simulated traceroute visualization
- Supports manual target IPs
- No external dependencies beyond curl
- Single portable bash script


### Usage Examples

```bash
geostalk                    # current visitor / machine
geostalk 1.1.1.1            # Cloudflare DNS
geostalk 8.8.8.8            # Google DNS
geostalk 192.168.1.1 -f     # force query (still uses public databases)
```
