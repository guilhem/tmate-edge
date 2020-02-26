# tmate-edge

run tmate on edge

## Why

You may want a backdoor to access your edge servers

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
