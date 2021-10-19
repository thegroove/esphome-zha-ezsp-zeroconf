# esphome-zha-ezsp-zeroconf

Experimental! ESPHome component with tcp-to-serial and zeroconf feature for autodiscovery.

Advertises in this format:
```
_esphome_zb_gw_efr32._tcp      local
   hostname = [esphome_zb_gw_efr32.local]
   address = [172.16.0.174]
   port = [8080]
   txt = ["version=1.0" "location=basement" "radio_type=ezsp" "baud_rate=115200" "data_flow_control=software"]
```
(use e.g. avahi-browse -r -a to see this)
