Missing configuration files will be moved from /opt/jboss/default/config to here 

Copy new keystores and/or standalone-full.xml here to override JBoss configuration

Default configuration is:
1. .geospass - file with geoserver login/password
2. .lepass - file with le login/password
3. client.truststore - keystore with trusted client certificates (for incoming ssl connections)
4. rtls-roles.properties - roles which will be given upon connecting by one of trusted client certificates
5. srv.keystore - JBoss ssl listener certificate, also used for le outbound connections
6. srv.truststore - trusted CA certificates
7. standalone-full.xml - server configuration
