# About

Janda Baper Group

# Open Ports

<br>OpenSSH : 22
<br>Dropbear : 143, 109, 110, 456
<br>SSL : 443, 442 (openvpn SSL)
<br>OpenVPN : 1194
<br>Squid3 : 80, 8080 (limit to IP SSH)
<br>Config OpenVPN: http://myip:81/janda.zip
<br>badvpn : badvpn-udpgw port 7500
<br>nginx : 81

# Installation

apt-get update && apt-get upgrade -y && wget https://github.com/janda09/install/raw/master/install && chmod +x install && ./install

# Type MENU to display a list of commands

# Note
If there is an error during restart, then restart manually.
after the installation is complete restart stunnel4 manually.
