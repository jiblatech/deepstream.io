## Modified version of deepstream that allows inspection

The following endpoints are available to retrieve records, events and rpc's:

```
http://localhost:3090/records

http://localhost:3090/events

http://localhost:3090/rpc
```

To start rest server on a different port use:

```bash
bin/deepstream start \
                --port 6021 \
                --rest-port 3091
```