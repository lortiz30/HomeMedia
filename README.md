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

- Install Ubuntu Server

- If default partitioning was used we need to fix it . Follow this guide:

  https://askubuntu.com/questions/1106795/ubuntu-server-18-04-lvm-out-of-space-with-improper-default-partitioning

  - Set static ip:
 
    https://www.freecodecamp.org/news/setting-a-static-ip-in-ubuntu-linux-ip-address-tutorial/

    - Mount the NAS disk
   
    https://www.truenas.com/community/threads/nfs-share-mounting.110331/

    Install Arr stack

https://github.com/automation-avenue/youtube-39-arr-apps-1-click

  



