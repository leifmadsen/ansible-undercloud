# ansible-undercloud
Instantiate a TripleO undercloud relatively easily with Ansible

## Pre-requisites

* Assumes a CentOS 7.3 host
* External NIC must be configured with a bridge (with device name specified as `virt_host_bridge_devicename` in `vars/virt_host.yml`)

## Diagram (WIP)

![basic diagram](http://i.imgur.com/5yXWjlw.png)
