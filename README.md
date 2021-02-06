# ansible-openvpn-exporter

## Intro

Deploy [openvpn_exporter](https://github.com/kumina/openvpn_exporter) using ansible.

## Description

This ansible role contains the binary of the kumina exporter and is copied to the
target hosts. The commit which it is build from is `9d468c0` (Jun 29, 2020).

## Role Variables

The default values of the following variables can be customized and are stored in
[defaults/main.yml](defaults/main.yml).

```yml
openvpn_exporter_system_group: "root"
openvpn_exporter_system_user: "root"
openvpn_exporter_status_file: "/etc/openvpn/openvpn-status.log"
openvpn_exporter_listen_port: "9276"
```
