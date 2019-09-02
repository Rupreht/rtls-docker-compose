Missing configuration files will be moved from /opt/le/default/config to here 

So after first start this folder will be populated with default configuration

Copy new le configuration and/or certificate files to override default le container configuration

Default le configuration is:
1. le.conf - le configuration file
2. ca-cert.crt - ca certificate for inbound/outbound ssl connections validation
3. le-cert.pem - certificate in pem format with which ssl listener will start, also used for JBoss ssl outbound connections
4. .srvpass- file with JBoss username/password
