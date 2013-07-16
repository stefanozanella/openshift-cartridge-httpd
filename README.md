# OpenShift HTTPD Cartridge

This is a minimal cartridge for OpenShift that just configures the available
Apache server so it can be run as the current user.

The root of your application will be the `DocumentRoot` (indexing not allowed, btw).

To use the cartridge in OpenShift Express, insert the following URL when asked
to select cartridge to use:

```
http://cartreflect-claytondev.rhcloud.com/reflect?github=stefanozanella/openshift-cartridge-httpd
```
