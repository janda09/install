# About

Janda Baper Group

# Open Ports

<br>OpenSSH : 22
<br>Dropbear : 80, 143, 109, 443, 456
<br>SSL : 444, 442 (openvpn SSL)
<br>OpenVPN : 1194
<br>Squid3 : 3128, 8080 (limit to IP SSH)
<br>Config OpenVPN: http://myip:81/janda.zip
<br>badvpn : badvpn-udpgw port 7500
<br>nginx : 81

# Installation

apt-get update && apt-get upgrade -y && wget https://raw.githubusercontent.com/janda09/install/master/janda.sh && chmod +x janda.sh && ./janda.sh

# Type MENU to display a list of commands

# Note
If there is an error during restart, then restart manually.
<br>After the installation is complete restart stunnel4 manually.
