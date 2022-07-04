# Home Lab
## current setup

| Rack |
| --- |
| Rack Shelf |
|     |
| 24 Port 1G switch |
| PFsense Firewall |
|     |
|     |
|     |
| Virtualization Server / NAS |
|     |
|     |
| Gaming PC |
|     |
|     |
|     |

## Docker apps (running in docker swarm)

| App | Running? | Description |
| ---| --- | --- |
| Portainer | Y | Docker manager GUI |
| Ghost | Y | Static CMS web site (this!) |
| code-server | Y | VS code self hosted through browser |
| motioneye | N | Home security camera monitoring |
| draw.io | N | Self hosted vector drawing package |
| syncthing | N | File syncronisation and backup software |
| nextcloud | N | Self hosted cloud resources and apps in one |

## VMs on Proxmox

| VM | Running ? | Description |
| --- | --- | --- |
| OpenMediaVault | Y | NAS software |
| Ubuntu server | Y | Deployer node |
| Docker master | Y | Master node running portainer |
| Docker worker1 | Y | Worker node |
| Docker worker2 | Y | Worker node |
| k3s master1 | N | Master node
| k3s master2 | N | Master node
| k3s worker1 | N | Worker node
| k3s worker2 | N | Worker node
| k3s worker3 | N | Worker node
