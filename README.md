# ffplayout-docker

Complete playout solution with [engine](https://github.com/ffplayout/ffplayout-engine), [API](https://github.com/ffplayout/ffplayout-api), [Web GUI](https://github.com/ffplayout/ffplayout-frontend) and [srs rtmp/hls server](https://github.com/ossrs/srs).

```
docker-compose up -d
```

A debian like host system, with a resent docker version, is recommand.

In **config** folder you found all config files you need, for the engine, srs and nginx (runs in ffplayout-frontend).

Default login is:
- user: **admin**
- pass: **admin**
