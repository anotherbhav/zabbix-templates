# zabbix-templates


# Template Palo Alto

# Features
- imports value map
- discovers + graphs interfaces
  - this includes VPN tunnel interfaces
- discovers all fans
- discovers internal temperature components
- graphs TCP and UDP sessions.


# Tested On
- Zabbix 3.2
- Zabbix 3.4
- Palo Alto - PANOs 8.x
- PANOs 8.1

# Fixed/Changed
- fixed incorrect Core/System temperature monitoring
- disabled all alerts for CPU thresholds between 0-60%
  - these can still be enabled if you still use them

# Other

## Thanks

Initial template based off the following work (thanks!):
- https://share.zabbix.com/network_devices/palo-alto/template-palo-alto-pa-200-pan-os-ver-6-0-x
- hasn't been updated since 2016, and not sure if its maintained any longer
