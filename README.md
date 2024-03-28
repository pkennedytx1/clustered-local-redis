# Clustered Local Redis

This is just a template or starting place to integrate clustered Redis instances into local development.

The only thing to note is in the Dockerfile if you run on windows, linux, or intel mac, you might need to change the base image outlined in the file.

For Apple Silicon users the platform tag has been provided in the FROM in the Dockerfile

To start:
```docker compose up```

You can connect to the exposed port outlined in the compose file.