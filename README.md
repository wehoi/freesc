<p align="center">

# สคริป XRAY MULTI PORT 
- สคริปสำหรับ  XRAY PORT 443/80 Moded By JAVA 
- เครดิต  SL
  
# พอร์ต XRAY TLS
- TROJAN WS        : 443
- TROJAN GRPC      : 443
- SHADOWSOCKS WS   : 443
- SHADOWSOCKS GRPC : 443
- VMESS WS         : 443
- VMESS GRPC       : 443
- VLESS WS         : 443
- VLESS GRPC       : 443

# พอร์ต XRAY HTTP
- TROJAN WS        : 80
- TROJAN GRPC      : 80
- SHADOWSOCKS WS   : 80
- SHADOWSOCKS GRPC : 80
- VMESS WS         : 80
- VMESS GRPC       : 80
- VLESS WS         : 80
- VLESS GRPC       : 80

# OS ที่รองรับ
- Debian 9 
- Debian 10


# เงื่อนไขการรันสคริป
- จำเป็นต้องมี VPS
- จำเป็นต้องมีบัญชี Cloudflare
- จำเป็นต้องมีโดเมน หากไม่มีโดเมน จำเป็นต้องแปลงไอพี สามารถหาได้ที่เว็บฟรีต่างๆ

# วิธีการรันสคริป
- ล๊อกอิน VPS แล้ว ก๊อปลืงก์นี้ไปวางใน VPS
```
apt update && apt upgrade -y && update-grub && sleep 2 && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt upgrade && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/wehoi/freesc/main/setup.sh && chmod +x setup.sh && ./setup.sh
```
- หากลงรันสคริปเรียบร้อยแล้ว สามารถเข้า VPS แล้วพิมพ์

```
menu
```
- เรียบร้อย

# หากมีเจอปัญหาในการรันสคริป สามารถติดต่อได้ที่ 
Whatsapp : +66934567688 
Telegram : https://t.me/java00777
Line : https://line.me/ti/p/V8OKlaIlra
