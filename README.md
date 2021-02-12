# Web socket and Apche httpd example for various tests.
Apache httpd since 2.4.44 support since  the proxy check_trans hook that allows a better processing of the websocket upgrades.
If your httpd is older use the patch:
http://people.apache.org/~covener/patches/wstunnel-decline.diff

# WebSocket and mod_cluster/mod_proxy

# Test for MODCLUSTER-580 and JBCS-291

See https://issues.redhat.com/browse/JBCS-291 and https://issues.redhat.com/browse/MODCLUSTER-580
