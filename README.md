# NETZ-XRAY
Installasi Netz-Xray Multi Port 443 & 80

# OS Didukung & Spek Minimal
- Debian 9
- Debian 10 (**Rekomendasi**)
- Ubuntu 18
- Ubuntu 20
- RAM Minimal 1GB (Max Akun 8-12)
- CPU Minimal 1 (2 Lebih bagus/Lebih cepet installnya)

# Fitur
- VMESS WS TLS 443
- VMESS WS NON TLS 80
- VMESS GRPC 443
- VLESS WS TLS 443
- VLESS GRPC 443
- TROJAN WS TLS 443
- TROJAN GRPC 443
- SHADOWSOCKS WS 443
- SHADOWSOCKS GRPC 443

# Cara Daftarin IPnya
1. Harus punya akun github
2. Fork & Stars Repo Ini
3. Edit Di Repo Kamu File register.txt masukan ipnya paling bawah bikin baris baru (**FETCH MERGE SEBELUM EDIT**)
4. Lalu pergi ke tab pull request kamu submit aja ke repo utamaku
5. Langsung diterima (Kalo ga sibuk)

# Cara Insttallnya
1. VPS baru dibikin (hanya bisa untuk KVM)
2. Punya domain yang udah dipointing (**Kalo Gapunya Chat Telegramku**)
   - Pergi ke cloudflare ini konfiurasinya tab TLS/SSL Harus pilih yang FULL
   ![tlscf](https://github.com/adisubagja/AutoScriptXray/blob/master/img/tls-cf.jpg?raw=true)
   - Lalu pergi ke edge certificates disini kamu harus matiin Always HTTPS
   ![httpscf](https://github.com/adisubagja/AutoScriptXray/blob/master/img/https-cf.jpg?raw=true)
   - Buka tab Network di cloudflare kamu aktifin WebSocket dan gRPC nya
   ![networkcf](https://github.com/adisubagja/AutoScriptXray/blob/master/img/network-cf.jpg?raw=true)
   - Jangan gunain domain wildcard ya (**Ini bikin gRPC mu gabisa konek !!!**)
3. Login VPS kamu pakai **root** Ya
4. Ini kode instalasinya tinggal paste aja
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt upgrade && apt install wget && apt install curl && apt install screen && wget -q https://raw.githubusercontent.com/adisubagja/AutoScriptXray/master/adi.sh && chmod +x adi.sh && screen -S netzinstall ./adi.sh
```
**ALTERNATIF KALO GAGAL**
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt upgrade && apt install wget && apt install curl && apt install screen && wget -q https://cdn.statically.io/gh/adisubagja/autoscriptxray/master/adi.sh && chmod +x adi.sh && screen -S netzinstall ./adi.sh
```
5. Masukin domain kamu terus enter deh
6. Tunggu ampe selesai nanti reboot sendiri

# Perintah
- Ketik `menu` Detail Lebih Lanjut

# QnA
- Question : Kenapa akun saya gakonek bang?
- Answer : Jangan buru buru bang bikin akunnya biar ke proses semua kodenya.
- Question : Gapunya github bang?
- Answer : PM aja Telegramku !
- Question : Bang port 80 gajalan tapi di infonya aktif ?
- Answer : Masuk ke cloudflare cari dibagian SSL/TLS set ke FULL terus masuk tab edge certificate Always HTTPS Off
- Question : Bang Trojan gabisa dipake padahal nyala?
- Answer : Masuk Cloudflare set SSL/TLS ke Full
- Question : Bang gRPC ganyala?
- Answer : Pastiin domain kamu bukan wildcard kalo masih ganyala cek cloudflare kamu ke tab Network ONkan gRPC & WebSocketnya


# Laporin Erorr
- Telegram : https://t.me/adisubagja
- Telegram Group : https://t.me/+qmkQdAxx6_MxZjll

# Donasi / Support
- Qris
![qris](https://github.com/adisubagja/AutoScriptXray/blob/master/img/qris.jpg?raw=true)
- Dana/Ovo/Gopay
  - 082113695382


## Stargazers over time

[![Stargazers over time](https://starchart.cc/adisubagja/AutoScriptXray.svg)](https://starchart.cc/adisubagja/AutoScriptXray)