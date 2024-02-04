# Update-VPS-Scripts
Update VPS Scripts
========================================================================================================================================
开放端口【防火墙】
iptables -I INPUT -p tcp --dport 40031 -j ACCEPT

V2Ray一键脚本
[p#1 参数名]source <(curl -sL https://multi.netlify.app/v2ray.sh) --zh

综合工具箱
wget -O box.sh https://raw.githubusercontent.com/BlueSkyXN/SKY-BOX/main/box.sh && chmod +x box.sh && clear && ./box.sh

Linux 系统信息+网络带宽及硬盘读写速率。
wget -qO- bench.sh | bash

最全测试脚本
curl -fsL https://ilemonra.in/LemonBenchIntl | bash -s fast

显示延迟、抖动
bash <(wget -qO- https://bench.im/hyperspeed)

启动哪吒
./nezha.sh

ArgoX for VPS
bash <(wget -qO- https://raw.githubusercontent.com/fscarmen/argox/main/argox.sh)

ArgoX-启动
bash <(wget -qO- https://raw.githubusercontent.com/fscarmen/argox/main/argox.sh)

SingBox-启动
bash <(wget -qO- https://raw.githubusercontent.com/fscarmen/sing-box/main/sing-box.sh)

SBX
bash <(wget -qO- https://raw.githubusercontent.com/fscarmen/sing-box/main/sing-box.sh)[p#1 -n]

VPS一键脚本工具 v8.8.8
curl -fsSL https://raw.githubusercontent.com/eooce/ssh_tool/main/ssh_tool.sh -o ssh_tool.sh && chmod +x ssh_tool.sh && ./ssh_tool.sh

SINGBOX一键脚本
bash <(curl -Ls https://gitlab.com/rwkgyg/sing-box-yg/raw/main/sb.sh)

===========================================================================================================4thFeb/24

SpeedTest
bash <(wget -qO- https://down.vpsaff.net/linux/speedtest/superbench.sh)

科技lion脚本
curl -sS -O https://raw.githubusercontent.com/kejilion/sh/main/kejilion.sh && chmod +x kejilion.sh && ./kejilion.sh
