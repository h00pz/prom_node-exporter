# prom_node-exporter
this is an ansible role to install the linux node-exporter

#example inventory
[exporters]
host-1 ansible_host=1.1.1.100 ansible_user=ubuntu

[prometheus]
prom-1 ansible_host=1.1.1.1 ansible_user=ubuntu
