# Script SinglePort By Reyz-V4

 <h2 align="center">AutoScript VPN By Reyz <img src="https://img.shields.io/badge/Version-ReyzV4.0-blue.svg"></h2>


<p align="center"><img src="https://i.postimg.cc/D06X0V5g/IMG-20221211-235224.jpg"


<h2 align="center"> Supported Linux Distribution</h2>
<p align="center"><img src="https://d33wubrfki0l68.cloudfront.net/5911c43be3b1da526ed609e9c55783d9d0f6b066/9858b/assets/img/debian-ubuntu-hover.png"></p>
<p align="center"><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=blue"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2011&message=Bullseye&color=blue"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2018&message=18.04 LTS&color=blue"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2020&message=20.04 LTS&color=blue"></p>

<p align="center"><img src="https://img.shields.io/badge/Service-OpenSSH-success.svg"> <img src="https://img.shields.io/badge/Service-Dropbear-success.svg">  <img src="https://img.shields.io/badge/Service-Websocket-success.svg"> <img src="https://img.shields.io/badge/Service-BadVPN-success.svg">  <img src="https://img.shields.io/badge/Service-Stunnel-success.svg">  <img src="https://img.shields.io/badge/Service-OpenVPN-success.svg">  <img src="https://img.shields.io/badge/Service-Squid3-success.svg">  <img   src="https://img.shields.io/badge/Service-Webmin-success.svg">  <img src="https://img.shields.io/badge/Service-OHP-success.svg">  <img
src="https://img.shields.io/badge/Service-Xray-success.svg">  <img src= "https://img.shields.io/badge/Service-SSR-success.svg">  <img src="https://img.shields.io/badge/Service-Trojan Go-success.svg"> <img src="https://img.shields.io/badge/Service-Trojan-success.svg"> <img src="https://img.shields.io/badge/Service-WireGuard-success.svg"> <img src="https://img.shields.io/badge/Service-Shadowsocks-success.svg">

## Commands : <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=powershell&label=Shell&message=Bash%20Script&color=lightgray">

## Update & Upgrade First Your VPS for Debian 10 & 11

  ```html
  apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot

  ```

## Update & Upgrade First Your VPS for Ubuntu 18.04 & 20.04

  ```html
  apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && sleep 2 && reboot

  ```
 
## INSTALLATION SCRIPT 
  ```html
apt update && apt upgrade -y && apt install -y wget screen && wget -q https://raw.githubusercontent.com/GH-reyz/vpn/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh

   ```

     >>> Service & Port
   - OpenSSH                 : 22
   - SSH Websocket           : 2082 [OFF]
   - SSH SSL Websocket       : 222
   - OHP SSH                 : 6967
   - OHP DBear               : 6968
   - OHP OpenVPN             : 6969
   - OpenVPN                 : TCP 1194, UDP 2200, SSL 442
   - Stunnel4                : 447, 777
   - Dropbear                : 109, 143
   - Squid Proxy             : 3128, 8080
   - Badvpn                  : 7100-7900
   - Nginx                   : 81
   - VLess TCP XTLS          : 443
   - XRAY  Vmess TLS         : 435
   - XRAY  Vmess None TLS    : 95
   - XRAY  Vless TLS         : 443
   - XRAY  Vless None TLS    : 80
   - XRAY  Vmess Grpc        : 999
   - XRAY  Vless Grpc        : 880
   - XRAY  Trojan Grpc       : 653
   - Trojan                  : 8443
   - Trojan Go               : 2096
   >>> Server Information & Other Features
   - Timezone                : Asia/Kuala_Lumpur (GMT +8)
   - Fail2Ban                : [ON]
   - Dflate                  : [ON]
   - IPtables                : [ON]
   - Auto-Reboot             : [ON]
   - IPv6                    : [OFF]
   - Autoreboot On           : 7:00 AM GMT +8
   - Autobackup Data
   - AutoKill Multi Login User
   - Auto Delete Expired Account
   - Fully automatic script
   - VPS settings
   - Admin Control
   - Change port
   - Restore Data
   - Full Orders For Various Services

## Credit :
*   GHReyz / ReyzV4

<p align="center">
  <a><img src="https://img.shields.io/badge/Copyright%20©-PADU%20AutoScriptVPN%202022.%20All%20rights%20reserved...-blueviolet.svg" style="max-width:200%;">
    </p>
   </p>
