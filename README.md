# Apache CouchDB 2.0 Dockerfile

This docker file builds and runs Apache CouchDB 2.0 on top of the debian:jessie image. See Dockerfile or http://docs.couchdb.org/en/2.0.0/install/unix.html for more information.

- CouchDB root: `/couchdb`
- CouchDB executable: `/couchdb/bin/couchdb`
- CouchDB data directory: `/couchdb/data`
- CouchDB config directory: `/couchdb/etc`
-- Contains an empty local.ini that may be replaced for configuration.
- CouchDB log directory: `/couchdb/var/log`
