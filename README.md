# BitTorrent Sync

Docker container for BitTorrent Sync

Run with:

```
docker run -d --name="Sync" \
        --net="bridge" \
        -p 8888:8888/tcp \
        -p 5555:5555/tcp \
        -p 3838:3838/udp \
        -v "/mnt/user/appdata/sync-v1.3.109":"/config":rw \
        iarp/sync-v1.3.109
```

