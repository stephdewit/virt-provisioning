# Abstract

Unattended installations of virtual machines.

It's a wrapper script around `virt-install`.

# Usage

`provision-vm test-debian`

Install a new instance of a Debian server.

`provision-vm -o centos -r 4096 test-centos`

Install a new instance of a CentOS server with 4 GiB of memory.

# Caveats

There is a lot of hardcoded stuff related to my server configuration and my personal preferences.
