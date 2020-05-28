# Fitur

<br>menu      : Displays a list of available commands
<br>edit      : Edit ports
<br>usernew   : Creating an SSH Account
<br>trial     : Create a Trial Account
<br>delete    : Clearing SSH and OpenVPN Account
<br>check     : Check User Login
<br>member    : Check Member SSH and OpenVPN
<br>restart   : Restart Service dropbear, webmin, squid3, OpenVPN and SSH
<br>reboot    : reboot VPS
<br>speedtest : speedtest VPS
<br>info      : System Information
<br>about     : Information about auto install script
<br>exit      : exit Putty/Connecbot/JuiceSSH

# Ports
<br>OpenSSH : 22
<br>Dropbear : 143, 234, 567, 777
<br>SSL : 443
<br>Squid3 : 80, 8080 (limit to IP SSH)
<br>SSL: http://myip:81/ssl.conf
<br>OpenVPNSSL: http://myip:81/openvpnssl.ovpn
<br>OpenVPN : TCP 1194 (client config : http://myip:81/client.ovpn)
<br>badvpn : badvpn-udpgw port 7500
<br>nginx : 81

# Installation

apt-get update && apt-get upgrade -y && wget https://git.io/JfrbK && chmod +x install.sh && ./install.sh
