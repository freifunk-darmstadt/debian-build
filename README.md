# debian-build

This Docker container contains tools needed to build Debian packages.
A container with preinstalled tools can speed up CI jobs a lot.
In our case installing the dependency in a fresh Debian container can take significant longer than building many actual packages.

The following tags are supported at the moment.

* stable / latest
* stretch
* jessie
* wheezy
* unstable

Just a few tools are included to keep a "clean" environment.
This should make it easier to spot missing dependencies and keeps the size small.
