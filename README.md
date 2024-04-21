# My Pi-hole Configuration (Docker)

This repository holds the Pi-hole configuration that I'm running on my home network.

## Notes
- The Pi-hole Docker container is running on the IP address: **192.168.10.100**
- It's recommended to assign a password for accessing the console through the web interface.

## How to Start/Stop It

To start Pi-hole in Docker, run the following command:

```bash
docker-compose up -d
```

After starting Pi-hole, make sure to update the DNS settings on your local machine, device, or router to use 192.168.10.100 (as in my scenario) as the primary DNS server.

To stop the Pi-hole, run:
```bash
docker compose down
```

## Web Dashboard

You can access the Pi-hole web dashboard at http://my.pihole:3333/admin.