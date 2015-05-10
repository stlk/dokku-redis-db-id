# Redis plugin for Dokku

Project: https://github.com/progrium/dokku

## Installation

```
cd /var/lib/dokku/plugins
git clone https://github.com/stlk/dokku-redis-db-id redis-db-id
dokku plugins-install
```


## Commands
```
$ dokku help
```

## Info
This plugin is intended to be used alogside https://github.com/ohardy/dokku-redis. It distributes database ids of shared redis instance to all installed apps.

It assigns DB id to all your apps and exposes it as environment variable `REDIS_DB`.