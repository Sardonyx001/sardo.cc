# \*arr stack

## intro

- A single docker compose file for Radarr, Sonarr, and Bazarr.
  Along with other services like Lidarr, Readarr, Whisparr et al they are referred
  to as "*Arr", "*Arrs", "Starr", or "Starrs".
- They are designed to automatically grab, sort, organize, and monitor your
  Music, Movie, E-Book, or TV Show collections for Lidarr, Radarr, Readarr,
  Sonarr, and Whisparr; and to manage your indexers and keep them in sync with
  the aforementioned apps for Prowlarr.
- learn more [here](https://wiki.servarr.com/)

## host directory tree

```tree
/data
├── media
│   ├── books
│   ├── movies
│   ├── music
│   └── tv
└── torrents
```

_ps: make sure to enable `Connect To Predefined Network` in the `configuration`
menu on Coolify so these services can talk to each other_
