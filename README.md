eventapi
======================

### About

Source for a docker container for a node-red based event pub/sub notification and API service.

repo is synced with docker hub at brianapley/eventapi.



## Launching via docker hub (example)

```
docker run -it -p 1880:1880 -v nrdata:/data --name eventapi brianapley/eventapi
```

Once launched, UI can be accessed via http://host:1880/.

