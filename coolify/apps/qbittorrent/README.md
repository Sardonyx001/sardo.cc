# qbittorent with vuetorrent webui

For downloading precious linux ISOs of course!
Thanks a lot to the [VueTorrent team](https://github.com/VueTorrent/VueTorrent)

## things to look out for

Make sure to edit volume mappings before deploying

```yaml
volumes:
  - "data-qbittorrent:/config"
  - "<WHERE-TO-SAVE-DOWNLOADS>:/downloads"
  - "<WHERE-TO-SAVE-TORRENTS>:/torrents"
```

ps: make sure the container has appropriate permissions
to access these directories and the files inside them
