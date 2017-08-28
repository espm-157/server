# server

Public config files for ESPM server.

- `docker-compose.yml`: All services (`caddy` reverse proxy, `RStudio` Server, and `netdata` monitoring) are provided through docker containers orchastrated using this compose file.
- `site/` config files for the `caddy` reverse proxy, must be adjusted to the appropriate domain name.
- `netdata.conf` Basic configuration file cor `netdata` to allow extended logging.  


The ESPM server is hosted on NSF XSEDE's Jetstream Cloud under an educational allocation.
