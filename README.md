# install
<b><br>OpenSSH : 22
<br>Dropbear : 143, 234, 567, 777
<br>SSL : 443
<br>Squid3 : 80, 8080 (limit to IP SSH)
<br>SSL: http://myip:81/ssl.conf
<br>OpenVPNSSL: http://myip:81/openvpnssl.ovpn
<br>OpenVPN : TCP 1194 (client config : http://myip:81/client.ovpn)
<br>badvpn : badvpn-udpgw port 7500
<br>nginx : 81

Auto-Installer

apt-get update && apt-get upgrade -y && wget https://raw.githubusercontent.com/janda09/install/master/install.sh && chmod +x install.sh && ./install.sh
