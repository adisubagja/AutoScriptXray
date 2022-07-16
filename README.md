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

# How to Register Installation
1. Must have github account
2. Fork & Stars repo
3. Edit on our repo add 1 ip addres/acc github
4. Then make Pull-Request
5. Will Approved (If Im Not Busy From RL)

# Guide Install
1. Fresh VPS Created (Only Support KVM)
2. Have Domain & Must be pointing DNS
   - Please setup cloudflare using Flexible on TAB TLS/SSL
   - Always HTTPS Must be Off
   - Setup Tab NETWORK Enable WebSocket & GRPC
   - Please no using Wildcard (THIS MAKE GRPC NOT WORKING ON MY SCRIPT !!!)
3. Login VPS Using ROOT User
4. Just Copy
`apt update && apt upgrade && wget -q https://raw.githubusercontent.com/adisubagja/AutoScriptXray/master/adi.sh && chmod +x adi.sh && ./adi.sh`
5. Put Domain & Enter
6. Enjoy

# Report Bug

Telegram : https://t.me/adisubagja
Telegram Group : https://t.me/+qmkQdAxx6_MxZjll