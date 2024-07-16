Telegraf
========

An Ansible role to install, configure, and manage [Telegraf](https://github.com/influxdb/telegraf), the plugin-driven server agent for reporting metrics into InfluxDB.

Requirements
------------

Prior knowledge/experience with InfluxDB and Telegraf is highly recommended. Full documentation is available [here](https://docs.influxdata.com).

Installation
------------

Clone the repository into  your roles directory


Role Variables
--------------

The high-level variables are stored in the `defaults/main.yml` file. The most important ones being:

```
# Channel of Telegraf to install (currently only 'stable' is supported)
telegraf_install_version: stable
```

More advanced configuration options are stored in the `vars/main.yml` file, which includes all of the necessary bells and whistles to tweak your configuration.

Dependencies
------------

No other Ansible dependencies are required. This role was tested and developed with Ansible 1.9.4.

Example Playbook
----------------

An example playbook is included in the `test.yml` file... 
