ENV VARS

Here is a list of environmental variables that are inspected by skylib.

SKYNET_BIND_IP=127.0.0.1
  IP Address for skynet services to bind to

SKYNET_MIN_PORT=9000
  The start of port range for skynet services to use

SKYNET_MAX_PORT=9999
  The end of port range for skynet services to use

SKYNET_REGION=unknown
	The service's self-reported region.

SKYNET_SERVICE_DIR=/usr/bin
  The directory where services are deployed to and the daemon will start them from
