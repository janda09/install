# About

Script autoinstaller for Debian 9 32 & 64 bit.

# Open Ports

<br>OpenSSH : 22
<br>Dropbear : 143, 109, 110, 456
<br>SSL : 443
<br>Squid3 : 3128, 8080 (limit to IP SSH)
<br>SSL: http://myip:81/ssl.conf
<br>OpenVPNSSL: http://myip:81/openvpnssl.ovpn
<br>OpenVPN : TCP 1194 (client config : http://myip:81/client.ovpn)
<br>badvpn : badvpn-udpgw port 7500
<br>nginx : 81

# Installation

apt-get update && apt-get upgrade -y && wget https://github.com/janda09/install/raw/master/install.sh && chmod +x install.sh && ./install.sh

# Type MENU to display a list of commands

# Note
If there is an error during restart, then restart manually.
