dnscrypt-autoinstall (changes IPs for resolv.conf - Debian 11 OK)
====================

## Decription
Installation and autoconfigure script for debian'ish systems and dnscrypt.

This script will install pre-req's, make & install dnscrypt and finally set it up
as a daemon service that runs on system startup. It also gives you the option to
choose which DNSCrypt service to use and easily reconfigure DNSCrypt and uninstall it.

This script should work on new(er) debian'ish releases.

Todo: proper init script, download newest version, handle failed download, fix quirks


## Installation
wget https://raw.github.com/bithostel-dev/dnscrypt-autoinstall/master/dnscrypt-autoinstall.sh && sudo bash dnscrypt-autoinstall.sh

