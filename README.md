# sd-workshop-docker

Docker Compose file for setting up the container for the December 13 Stable Diffusion workshop at the House of Connections, University of Groningen.

## Building and starting the container

Create a file `.env` where you define `WEB_USER` and `WEB_PASSWORD`. Optionally, also specify a CloudFlare tunnel token to setup a custom CloudFlare tunnel with `CF_TUNNEL_TOKEN`. The workspace location on the host can be specified with `WORKSPACE_HOST_LOCATION`. Build and start the container with `docker compose up`. 
