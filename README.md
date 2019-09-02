Compose files and volume directories with default container configurations are here

Be careful because if directories structure is not present when starting docker-compose,
 containers fail to start or start withh errors

Usages:
1. Change "image" field in docker-compose.yml for srv and le containers to prefered
 system version (tag name is identical with branch name)
2. run "docker-compose up -d" in this directory

It will launche 3 containers:
1. postgres - container with postgres database. Does not contain schema. Pure database
2. le - container with Locating Engine
3. srv - container with java + Jboss + geoserver + application.
 It will wait for postgres container to startup. Then, if schema rtls_pu does not exist
 (first launch), it creates new schema, role and tablespace
