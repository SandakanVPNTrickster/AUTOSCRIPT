<h1 align="center">AutoScriptVPS</h1>

<h3 align="center">Supported Linux Distribution</h3>
<p align="center"><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%209&message=Stretch&color=red"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=red"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2018&message=18.04 LTS&color=red"> </p>




# NOTE
- Free Script Install Lite Version 
- SSH, SSH-WS, Open VPN, V2ray Trojan and Wireguard
- Credit to Horas/Md

# ROOT GRANTED(CHANGE TO ROOT)

```html
sudo su
wget https://raw.githubusercontent.com/jinGGo007/VPS/main/grant-root && chmod +x grant-root && ./grant-root
  ```
  

# INSTALLATION AUTOSCRIPT

```html
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/jinGGo007/AUTOSCRIPT/main/setup.sh && chmod +x setup.sh && ./setup.sh
  ```
 - You must have domain before install this script 
 - Contact https://t.me/jinggo007 for register IP
 - 
  
<h3 align="center">Screenshots</h3>
<p align="center">
<img src="https://raw.githubusercontent.com/jinGGo007/AUTOSCRIPT/main/menu.jpg">

  
# INSTALLATION OHP ADDON

```html
wget https://raw.githubusercontent.com/jinGGo007/AUTOSCRIPT/main/ohpserver.sh && chmod +x ohpserver.sh && ./ohpserver.sh
  ```
   - Contact https://t.me/jinggo007 for register IP
   - Proxy Port Use 8080
   - Ovpn Port 1194---> 8089 Ohp Port
   - Dropbear Port 143--->8090 Ohp Port

  
# VPN SERVICES AND PORTS

- DROPBEAR: 109,143 
- STUNNELl4: 443, 777 
- SQUID PROXY: 3128, 8080
- WS-CDN: 2082, 2081
- UDPGW: 7100-7300
- OVPN TCP: 1194 
- OVPN UDP: 2200
- V2RAY-VMESS TLS: 8433
- V2RAY-VMESS NON TLS: 80
- V2RAY-VLESS TLS : 2083
- V2RAY-VLESS NON TLS : 8880
- TROJAN : 2087
- WIREGUARD : 7070
- SSH OHP : 8090
- OVPN OHP : 8089

------------------------------
- Contact:
- Telegram : https://t.me/jinggo007
