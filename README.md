# My Pi-hole configuration (Docker)

This repository holds the Pi-hole configuration that I'm running in my home network.

Notes:
- I am running the container on IP address: **192.168.10.100**
- You should assign a password for accessing the console through the web interface

## How to start/stop it

To start the Pi-hole in Docker, run following command:

```bash
docker compose up -d
```

Then, you have to update the update the DNS entries on your local machine/device or router. In my case, the primary DNS server is: **192.168.10.100**

To stop the Pi-hole, run:
```bash
docker compose down
```

## Web dashboard

Web dashboard is accessible here: http://my.pihole:3333/admin