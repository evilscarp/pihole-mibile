# pihole-mobile

Pihole+unbound docker-compose implementation for a local pihole service

## Requirements

This particular implementation uses 192.0.0.0/24 addresses, which are reserved
by IANA for protocol-specific applications.  The unbound server binds to 192.0.0.1:5253
by default.  This address needs to be resident on the host server before the container 
will launch.

## Credits

Based on work by:

* https://github.com/pi-hole/pi-hole
* https://hub.docker.com/r/mvance/unbound

