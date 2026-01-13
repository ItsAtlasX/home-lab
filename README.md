# home-lab
A repository covering the set up of my homelab run on a barebones ubuntu-server install
## Services 
  - Immich: Private Google Photos
  - Jellyfin stack: Media Playback and Requesting
    - Jellyfin: Media Playback
      - https://jellyfin.org/docs/general/installation/container
    - Jellyseer: Media Requesting
      - https://hub.docker.com/r/fallenbagel/jellyseerr
  - Arr* Stack
    - Radarr: Movie Manager
      - https://wiki.servarr.com/radarr
    - Sonarr: Show Manager
      - https://wiki.servarr.com/sonarr
    - Prowlarr: Search indexing tool
      - https://wiki.servarr.com/prowlarr
      - Flaresolver: gets around cloudflare for certain sources
        - https://hub.docker.com/r/flaresolverr/flaresolverr
    - Bazaar: Caption Manager
      - https://wiki.bazarr.media
  - Media Acquiring Stack
    - GlueTun With CyberGhost VPN
      - https://github.com/qdm12/gluetun
      - QBittorrent
        - https://hub.docker.com/r/linuxserver/qbittorrent
  - Crafty Controller: Minecraft Server WebUI
  - VaultWarden: Password manager
    - https://github.com/dani-garcia/vaultwarden
## Interface 
  - Portainer
