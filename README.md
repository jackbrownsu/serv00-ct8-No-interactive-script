# serv00-ct8无交互一键脚本合集
# 汇聚大佬们的脚本 
# 非cron保活版本，死了就重新安装一遍

## 一键四协议无交互安装脚本vmess-ws|vmess-ws-tls(argo)|socks5|tuic5，需设置环境变量 
必填环境变量：VMESS_PORT SOCKS_PORT TUIC_PORT 
可选环境变量：UUID SOCKS_USER SOCKS_PASS NEZHA_SERVER NEZHA_PORT NEZHA_KEY ARGO_DOMAIN ARGO_AU

## 一键tuic(nezha变量可选)

curl -s https://eooce.2go.us.kg/tu.sh | PORT=UDP端口 NEZHA_SERVER=admin.cn NEZHA_PORT=5555 NEZHA_KEY=abc123 bash

## 一键hy2(nezha变量可选)

curl -s https://eooce.2go.us.kg/2.sh | PORT=UDP端口 NEZHA_SERVER=admin.cn NEZHA_PORT=5555 NEZHA_KEY=abc123 bash




