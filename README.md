# junos-slax-vpn

This SLAX script creates a fully configured VPN within a designated group that can then be group applied into your running config.

## Installation

* Copy/upload the file to the device:

    `scp vpn.slax user@device:/var/db/scripts/op/`

* Run the script from the local file system, in *_operational_* mode:

    `op url /var/db/scripts/op/vpn.slax`

* Configure the script so it can be run by using it's name:

    `set system scripts op file vpn.slax`

## Usage ##

Run op vpn ? for complete listing on arguments.


