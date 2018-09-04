# CloudFoundry CLI for ARM

This is a Concourse pipeline to build the CloudFoundry CLI for ARM.

The `-termux` binaries have the location of `/etc/resolv.conf` changed to `/data/data/com.termux/files/usr/etc/resolv.conf` to make them work in the excellent [Termux](https://termux.com/) Android app.