- Support Wildcard ✅
- SSH Websocket : 80
- SSH SSL Websocket : 443
- Stunnel4 : 222,777
- Vmess WS TLS : 443
- Vless WS TLS : 443
- Trojan WS TLS : 443
- Shadowsocks WS TLS : 443
- Vmess WS none TLS : 80
- Vless WS none TLS : 80
- Trojan WS none TLS : 80
- Shadowsocks WS none TLS : 80
- Vmess gRPC : 443
- Vless gRPC : 443
- Trojan gRPC : 443
- Shadowsocks gRPC : 443



```
apt install wget -y && echo 1 > /proc/sys/net/ipv6/conf/all/disable_ipv6 && apt install -y bzip2 gzip coreutils screen curl unzip && apt install tmux -y && wget https://raw.githubusercontent.com/claudialubowitz26/supreme/aio/setup.sh && chmod +x setup.sh && tmux new-session -s script './setup.sh'
