# Grafana

This container provides the UI for the weather station using Grafana.
The base image is a custom version of [BalenaDash](https://github.com/balenalabs/balena-dash) originating from this [fork](https://github.com/hferentschik/balena-dash).
The reason for the for is to upgrade Grafana to 7.3.x in order to install the Grafana JSON datasource plugin.

The files in this directory are used to provision Grafana and create the actual weather dashboard.

## Misc

* [Grafana provisioning](https://grafana.com/docs/grafana/latest/administration/provisioning)
