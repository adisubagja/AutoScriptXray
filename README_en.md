# NETZ-XRAY
Installer Netz-Xray Multi Port 443 & 80

# OS Supported & Requirements
- Debian 9
- Debian 10 (Recommended)
- Ubuntu 18
- Ubuntu 20
- RAM Minimal 1GB (Max User 8-12)
- CPU Minimal 1 (2 For Faster/Great Installation)

# Feature
- VMESS WS TLS 443
- VMESS WS NON TLS 80
- VMESS GRPC 443
- VLESS WS TLS 443
- VLESS GRPC 443
- TROJAN WS TLS 443
- TROJAN GRPC 443
- SHADOWSOCKS WS 443
- SHADOWSOCKS GRPC 443

# How to Register Installation
1. Must have github account
2. Fork & Stars repo
3. Edit on our repo add 1 ip addres/acc github (**FETCH MERGE BEFORE EDIT**)
4. Then make Pull-Request
5. Will Approved (If Im Not Busy From RL)

# Guide Install
1. Fresh VPS Created (Only Support KVM)
2. Have Domain & Must be pointing DNS
   - Please setup cloudflare using FULL on TAB TLS/SSL
   ![tlscf](https://github.com/adisubagja/AutoScriptXray/blob/master/img/tls-cf.jpg?raw=true)
   - Always HTTPS Must be Off
   ![httpscf](https://github.com/adisubagja/AutoScriptXray/blob/master/img/https-cf.jpg?raw=true)
   - Setup Tab NETWORK Enable WebSocket & GRPC
   ![networkcf](https://github.com/adisubagja/AutoScriptXray/blob/master/img/network-cf.jpg?raw=true)
   - Please no using Wildcard (THIS MAKE GRPC NOT WORKING ON MY SCRIPT !!!)
3. Login VPS Using ROOT User
4. Just Copy
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt upgrade && apt install wget && apt install curl && apt install screen && wget -q https://raw.githubusercontent.com/adisubagja/AutoScriptXray/master/adi.sh && chmod +x adi.sh && screen -S netzinstall ./adi.sh
```
**IF FAILED TRY USING ALTERNATE**
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt upgrade && apt install wget && apt install curl && apt install screen && wget -q https://cdn.statically.io/gh/adisubagja/autoscriptxray/master/adi.sh && chmod +x adi.sh && screen -S netzinstall ./adi.sh
```
5. Put Domain & Enter
6. Enjoy

# Command
- Type `menu` for detail

# QnA
- Question : Why account not connected?
- Answer : Please check again, try check port open & create acc processing don't close using CTRL+C this make service not reload ! you must restart service all for back normally.
- Question : Gapunya github bang?
- Answer : PM aja Telegramku !


# Report Bug
- Telegram : https://t.me/adisubagja
- Telegram Group : https://t.me/+qmkQdAxx6_MxZjll

# Donasi / Support
- Qris
![qris](https://github.com/adisubagja/AutoScriptXray/blob/master/img/qris.jpg?raw=true)
- Dana/Ovo/Gopay
  - 082113695382
