# Shodan and Censys

## For Shodan:

### ✅ Example Queries:

- **IP info**:`https://www.shodan.io/host/202.70.90.4`
- **IP Cameras in Kathmandu**:`ip camera country:"NP" city:"Kathmandu"`
- **RDP in Nepal**:`country:"NP" port:"3389"`
- **SSH in Nepal**:`country:"NP" port:"22"`
- **Telnet Devices in Nepal**:`country:"NP" telnet`
- **MikroTik Routers in Pokhara**:`product:"MikroTik" country:"NP" city:"Pokhara"`
- **Fortinet Devices in Nepal**:`country:"NP" product:"Fortinet FortiGate"`

## For Censys

### ✅ Example Queries:

- **Hosts in Nepal**:`(nepal) and host.ip: *`
or`host.location.country_code = "NP"`
- **Open Port 21 in Nepal**:`(host.location.country_code = "NP") and host.services.port = "21"`
- **SSH (port 22)**:`(host.location.country_code = "NP") and host.services.port = "22"`
- **Telnet (port 23)**:`(host.location.country_code = "NP") and host.services.port = "23"`
- **RDP (port 3389)**:`(host.location.country_code = "NP") and host.services.port = "3389"`
- **Firewalls**:`(host.location.country_code = "NP") and host.services.labels.value = "FIREWALL"`
- **Hikvision Cameras**:`((location.country=Nepal) and labels="camera") and services.software.vendor="Hikvision"`