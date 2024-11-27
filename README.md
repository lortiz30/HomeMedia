# HomeMedia

Home Media will have 3 main componets:

**Gaspar** : A NAS server

**Bastarsar** : A headless server running qBitTorrent , Prowlarr, Radarr and Sonarr

**Melchor** : A Plex server

Gaspar will have an array of hard disks and will act an an NAS. Baltasar will index and get all the torrents and store them into Gaspar. Melchor will access Gaspar and serve the media on the Plex clients.

## Baltasar

Specs:

- i3 : No need of more processing
- 16GB RAM : For running Docker, Prowlarr, Sonar, Radar and qBitTorrent
- 250 GB HD : More than enough. The idea is to store store the media and torrents into the NAS

Installation

- Install Proxmox

https://www.proxmox.com/en/downloads/proxmox-virtual-environment/iso/proxmox-ve-7-4-iso-installer

- Get Ubuntu Server

 https://ubuntu.com/download/server

 - Upload ubuntu iso

 ![image](https://github.com/user-attachments/assets/0f8cd543-ee30-4872-a095-7d2ddad5fb0c)


- 



