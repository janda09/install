# Fitur

menu      : Displays a list of available commands
edit      : Edit ports
usernew   : Creating an SSH Account
trial     : Create a Trial Account
delete    : Clearing SSH and OpenVPN Account
check     : Check User Login
member    : Check Member SSH and OpenVPN
restart   : Restart Service dropbear, webmin
            squid3, OpenVPN and SSH
reboot    : reboot VPS
speedtest : speedtest VPS
info      : System Information
about     : Information about auto install script
exit      : exit Putty/Connecbot/
            JuiceSSH

# Ports
<b><br>OpenSSH : 22
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
