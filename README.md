# esphome-zha-ezsp-zeroconf

Experimental! ESPHome component with tcp-to-serial and zeroconf feature for autodiscovery.

Advertises in this format:
```
zha_ezsp_zeroconf  _ezsp._tcp  local
   hostname = [zha_ezsp_zeroconf.local]
   address = [172.16.0.174]
   port = [8080]
   txt = ["baud_rate=115200"]
```
(use e.g. avahi-browse -r -a to see this)
