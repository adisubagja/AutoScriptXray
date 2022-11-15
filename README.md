# Installer Netz-Xray

- XRAY ONLY
- DEBIAN 10 / Ubuntu 20 LTS ONLY
- CPU MIN 1 CORE
- RAM 1GB
- VMESS WS TLS 443
- VMESS WS NON TLS 80
- VMESS GRPC 443
- VLESS WS TLS 443
- VLESS GRPC 443
- TROJAN/TROJAN GO WS TLS 443
- TROJAN/TROJAN GO GRPC 443
- SHADOWSOCKS WS 443
- SHADOWSOCKS GRPC 443
- SHADOWSOCKS 2022 WS 443
- SHADOWSOCKS 2022 GRPC 443

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
rm -rf setup.sh && rm -rf adi.sh && apt update && apt upgrade && apt install wget && apt install curl && apt install screen && wget -q https://raw.githubusercontent.com/adisubagja/AutoScriptXray/master/adi.sh && chmod +x adi.sh && screen -S netzinstall ./adi.sh
```
**ALTERNATIF KALO GAGAL**
```
rm -rf setup.sh && rm -rf adi.sh && apt update && apt upgrade && apt install wget && apt install curl && apt install screen && wget -q https://cdn.statically.io/gh/adisubagja/autoscriptxray/master/adi.sh && chmod +x adi.sh && screen -S netzinstall ./adi.sh
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

# Kontak Admin
- Telegram : https://t.me/adisubagja

# Catatan & Riwayat
1. Script ini dulunya GRATIS !
2. Sekarang Installasi Minimal Donasi Rp.20.000 Kenapa bang jadi berbayar ? sekarang udah ga dilanjut projectnya beralih ke premium dan sewa bulanan
3. Jika kalian ingin menginstall ini secara paksa hubungi admin ! screenshoot donasi kalian kirim IPnya kudaftarin langsung (1 IP)
4. Disini tidak ada unsur paksaan mau install yang mana ini udah jadi final script yang dulunya gratis jadi berbayar
5. Terimakasih atas pengertiannya !

# Note Tambahan
Ketika kalian install script ini !
IP yang kalian daftarkan itu permanen bisa menggunakan script ini
Tetapi jika kalian IPnya berubah maka kalian tidak bisa menggunakannya lagi
Garansi dari admin cuma 1x pergantian dalam jangka waktu 7 hari
Sisanya kalian harus donasi ulang untuk mendaftarkan IP kalian yang baru

# Opini Pribadi
Script ini sangat cocok buat kebutuhan pribadi !
Jika kalian ingin untuk berjualan cobalah sewa script premium dari saya !

# Donasi / Support
- Qris
![qris](https://github.com/adisubagja/AutoScriptXray/blob/master/img/qris.jpg?raw=true)
- Dana/Ovo/Gopay
  - 082113695382

## Stargazers over time

[![Stargazers over time](https://starchart.cc/adisubagja/AutoScriptXray.svg)](https://starchart.cc/adisubagja/AutoScriptXray)