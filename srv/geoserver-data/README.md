The whole directory will be mounted on /opt/jboss/geoserver-data inside the container

If upon the start container finds out that directory /opt/jboss/geoserver-data is empty it copies default configuration there

So you could:
1. Copy new configuration here
2. Copy current configuration from here (to save it)
3. Clean directory, so default configuration to be initialized
