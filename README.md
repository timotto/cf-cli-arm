# CloudFoundry CLI for ARM

This is a Concourse pipeline to build the CloudFoundry CLI for ARM.

The `-termux` binaries have the location of `/etc/resolv.conf` changed to `/data/data/com.termux/files/usr/etc/resolv.conf` to make them work in the excellent [Termux](https://termux.com/) Android app.

# `cf login` workaround

The interactive `cf login` fails on Termux just like it fails on cygwin. To work around this issue use `cf login` and `cf auth` as described in the [GitHub issue 171](https://github.com/cloudfoundry/cli/issues/171#issuecomment-95137605).
