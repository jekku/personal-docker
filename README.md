# personal-docker
My disposable docker images for everyday use

# How do I use one?

For example you, want to use a disposable postgres:

```bash
docker-compose -f ./postgres/docker-compose.yml up # runs with logs, attached to bash
docker-compose -f ./postgres/docker-compose.yml up --detach # runs in the background
```

# Notes

Please remember to put down any service in your host that may conflict with ports.
