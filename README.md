# tmate-edge

[![tmate-edge](https://snapcraft.io//tmate-edge/badge.svg)](https://snapcraft.io/tmate-edge)
[![Snap Status](https://build.snapcraft.io/badge/guilhem/tmate-edge.svg)](https://build.snapcraft.io/user/guilhem/tmate-edge)

run tmate on edge

## Why

You may want a backdoor to access your edge servers.
Loosing control on an host can be as bad as loosing server itself.

_tmate-edge_ aim to provide a way to always have a shell on hosts.

As tmate host open connection to server, no need to configure NAT. Even if network change, it will reconnect to server.

## How

_tmate-edge_ is a _tmate_ client daemon.
It connect itself to a tmate server which work like a "bastion".
Connecting to the right session give you access to the right host.

_tmate-edge_ is a snap package and can be deployed on any snap-ready OS.
It's mainly designed for [Ubuntu Core](https://ubuntu.com/core).

## Security considerations

Use your own tmate server!

## Install

```bash
$ snap install tmate-edge
```

## Configure

| name | description | command |
| ---- | ----------- | ------- |
| api-key | registered api key | `snap set tmate-edge api-key=` |
| session-name | named session | `snap set tmate-edge session-name=` |
| server-host | hosted tmate server | `snap set tmate-edge server-host=` |
| server-port | | `snap set tmate-edge server-port=` |
| server-rsa-fingerprint | | `snap set tmate-edge server-rsa-fingerprint=` |
| server-ed25519-fingerprint | | `snap set tmate-edge server-ed25519-fingerprint=` |
