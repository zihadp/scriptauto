Automatic Script Setting VPS untuk berjualan ssh

==========

## How To Use

### Debian 7 32bit
```
wget -O ovz-install.sh https://raw.githubusercontent.com/zihadp/scriptauto/master/ovz-install.sh && chmod +x ovz-install.sh && ./ovz-install.sh
```
Tested on
* Debian 7 32 bit


## Description

### What's server included
* OpenSSH port 22, 143
* OpenVPN port 1194 tcp
* Dropbear port 109, 110, 443
* Squid port 8080 (limit to IP VPS)
* badvpn-udpgw port 7300

### What's features included
* Webmin http(s)://[ip]:10000/
* vnstat http://[ip]/vnstat/
* MRTG http://[ip]/mrtg/
* Timezone : Asia/Jakarta
* Fail2Ban : [on]
* IPv6     : [off]

### What's tools included
* axel
* bmon
* htop
* iftop
* mtr
* nethogs  

### What's script included
* screenfetch
* ps_mem.py (https://github.com/pixelb/ps_mem/)
* speedtest-cli (https://github.com/sivel/speedtest-cli)
* bench-network.sh
* user-login.sh
* create-user.sh
* user-delete.sh
* cekuser.sh

Openvpn
wget https://raw.github.com/arieonline/autoscript/master/dimas.debian
bash dimas.debian
